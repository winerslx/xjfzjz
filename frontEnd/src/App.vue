<el-container>
    <el-header style="height:20px;text-align:right;font-size:12px">
        <el-dropdown>
            <i class="el-icon-setting" style="margin-right:16px"></i>
            <el-dropdown-item>查看</el-dropdown-item>
            <el-dropdown-item>新增</el-dropdown-item>
            <el-dropdown-item>删除</el-dropdown-item>
        </el-dropdown>
        <span>网小虎</span>
    </el-header>

    <el-container style="height:500px; border:1px solid #eee">
        <el-aside width="200px" style="background-color:rgb(238,241,246)">
            <el-menu :default-openeds="['1']">
                <el-submenu index="1">
                    <template slot="title"><i class="el-icon-message"></i>导航一</template>
                    <el-menu-item-group>
                        <template slot="title">分组一</template>
                        <el-menu-item index="1-1">选项1</el-menu-item>
                        <el-menu-item index="1-2">选项2</el-menu-item>
                    </el-menu-item-group>
                </el-submenu>
            </el-menu>
        </el-aside>

        <el-main>
        </el-main>
    </el-container>
</el-container>

<style>
    .el-header{
        background-color:#B3C0D1;
        color:#333;
        line-height:60px;
    }
    .el-aside{
        color:#333;
    }
</style>
