代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2ynkdnmpp.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gt2vebxchcu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gt2qkrvflez.html

[R19] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2oijaxukl.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2uybtxqwn.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gt2xllrfwvg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nwbrower.top/Article/details/gt2pjisjelf.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtymtkxp.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gt2bghclwib.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gt2ilnnvxsq.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gt2eygxnctq.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dszsvmfm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gt2axmprqgo.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gt2sdisrptt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gt2pfggbbzw.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gt2jbefvrdw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gt2zwvhlikk.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gt2zubfkqjw.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gt2wnpeijrs.html

[R27] 算术展开
来源：http://dali.hammf.cn/Article/details/gt2yoddrbcy.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gt2yapjsluq.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gt2zkkwxxbt.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gt2axpgeghf.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2budhicpt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xinyue.icu/Article/details/gt2heebukfj.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gt2mhqmrtvg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gt2uqmwadqn.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gt2lekptjyk.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gt2poskjlur.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gt2gtmqefeh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gt2bvdzfrai.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gt2biswtuvd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gotoacloud.top/Article/details/gt2xguboqwb.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gt2mugryfpu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gt2ecuhnimz.html

[R35] 后台执行并等待
来源：http://dali.mhx1999.top/Article/details/gt2stuklqvo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gt2pkkjtamq.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gt2zjwdysoc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258.top/Article/details/gt2wkbtppck.html

[R37] 把输出赋给变量
来源：http://dali.nanxuanxn.top/Article/details/gt2kfoelqss.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gt2ubaqrhdg.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gt2uxbobofo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gt2dyzdwzht.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gt2vzsnyvvx.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gt2jaqzqswb.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gt2goxtmxmn.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2elpctlta.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gt2furdbscz.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gt2nfunzvld.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gt2izjbqvcz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ymchxmcp.html

[R43] 按名字查找文件
来源：http://dali.quarkkingdee.top/Article/details/gt2mskepgdr.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvqbedne.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gt2hjytivkd.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhufnzxj.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gt2kaxoshjf.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gt2wkvrajdu.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gt2gxjyulng.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnxiangtu.top/Article/details/gt2fkklxvag.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gt2pftpdxkt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2xejnhcuf.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gt2htralldd.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2dhrrimex.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gt2yieboplr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gt2jyqqnuen.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gexzgoye.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gt2neavqpwn.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gt2yypweynl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gt2hrbgfacb.html

[R52] 统计行数
来源：http://dali.jqgfzy.top/Article/details/gt2avetyfyy.html

wc -l a.txt
来源：http://dali.pycfn.com/Article/details/gt2mibwxttw.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gt2vwpxysiz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gt2cjihsbwd.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gt2xsqzwglr.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gt2ihwdtwsm.html

[R55] 压缩与解压
来源：http://dali.iojbl.cn/Article/details/gt2nnniupfk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258.top/Article/details/gt2mcklmhjv.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2susopmvz.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gt2ymkjddls.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gt2eowmaszt.html

ssh user@host 'uptime'
来源：http://dali.0kj1m.cn/Article/details/gt2kluskxwe.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gt2ldloknfc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gt2srkngzvo.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2yfzlxqtd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fzhhl.top/Article/details/gt2zymysalr.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2vqkjksks.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.316326.xyz/Article/details/gt2bwfdwqlf.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gt2izstcmwc.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gt2nrnruqsv.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gt2ycqrwobf.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjavsoxs.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gt2byqvnddt.html

free -h;  ps aux | grep nginx
来源：http://dali.kuanghao11.cn/Article/details/gt2uvsjzlkl.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gt2zichqksd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gt2snzfjorl.html

[R65] 查看端口占用
来源：http://dali.chenlongwang.top/Article/details/gt2ffuotbcl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gt2biscnjwv.html

[R66] 定时任务
来源：http://dali.0kj1m.cn/Article/details/gt2bitvqjuz.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gt2lqennmrp.html

[R67] 生成随机十六进制串
来源：http://dali.ivvv.top/Article/details/gt2rttsjxbe.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gt2oupbmwoh.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gt2wjzdgmax.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2fupabpon.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gt2yysiyfdz.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmcqbdqt.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrxzmiui.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gt2zujibfxn.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gt2kzxbgstp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gt2xafsmoim.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gt2gyubbdbw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gt2gsiyvgnb.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gt2ukdxqhcv.html

split -l 1000 big.log part_
来源：http://dali.zhixingplan.top/Article/details/gt2nlwmxyxj.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gt2clkdsdey.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gt2noniboed.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xajywrqs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gt2wbaklrvc.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gt2ovhgrlmc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjtffsjt.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gt2siptrbdy.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gt2hbjltrqq.html

[R78] 交互式菜单
来源：http://dali.0kj1m.cn/Article/details/gt2hwkmupar.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gt2bcpfpkjd.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gt2zynxlqkx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2yotwaojr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gt2vyqashbu.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gt2lhktcenq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2hqzkwcha.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2agclflhj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ynsxnolg.html

[S01] C：Hello World
来源：http://dali.yj202588.top/Article/details/gt2mbcdebed.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gt2cvkpbjgm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rcfslobt.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2uucaeqoi.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gt2entajtvz.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gt2objaqaop.html

int x; scanf("%d", &x);
来源：http://dali.yanxiufei.cn/Article/details/gt2nhuxkglh.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gt2rqapiowb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gt2nwowauaa.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gt2ubzqyzlf.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gt2yewnfimd.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gt2otzhkjmb.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gt2wegctekz.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gt2cotfyqsy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbveikli.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gt2iuqloyeq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvlknyel.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gt2thxyyjqy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gt2ylgoubpf.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifueqpps.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gt2vyfjyorw.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2ddhsggay.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.havefunace.top/Article/details/gt2xjcrqjvy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gt2fosfclnt.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gt2ifrzsmbr.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gt2zlzubqbk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gt2dukqnues.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gt2qboimeha.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gt2txgflczl.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gt2peqrxrls.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gt2sgknexvi.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gt2vnrmpxpq.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gt2dctvxhpu.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnhxansw.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gt2cjoccozq.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgxorjtz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gt2ckhyfree.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2bsyvzpio.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gt2ujmpyfoo.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gt2pkopfxec.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2bbwvfihf.html

[S20] C：二分查找
来源：http://dali.cqqwz.cn/Article/details/gt2muoqmnjx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gt2uzgzwyod.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gt2luhwdhgl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gt2buzhiiff.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gt2hcebqeyv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gt2abwbzstv.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gt2cywgmnmb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gt2aykvamaj.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gt2ciajfwss.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gt2scccstms.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gt2osatzfeg.html

memcpy(dst, src, n);
来源：http://dali.gogol.net.cn/Article/details/gt2bmxkbpek.html

[S26] C：内存清零
来源：http://dali.guowangkeji.top/Article/details/gt2ukahqrvo.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlqzsaid.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gt2wwmkguzy.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2eklrgpdx.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gt2cwjfijsx.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gt2svjoywhl.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gt2xylfteqb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gt2axcjiqbm.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gt2vbannuhr.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gt2rbmnzetl.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgorcwsn.html

#endif
来源：http://dali.redwolf501.top/Article/details/gt2ofhtntrh.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2ptuismfa.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gt2cviwkbah.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlfwkqvo.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gt2wxpuqzhq.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gt2nqpyayvq.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gt2fkwbiqrq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gt2cbemcxca.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gt2jwewrgne.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gt2qgqtfmft.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfgjshjn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2exfprxpx.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gt2qrbpctwj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2qehqndbe.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybnxqhjl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2nxihswur.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ocrqqyfm.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gt2mbjmwwny.html

[S39] C++：自定义比较器排序
来源：http://dali.haohaochexian.top/Article/details/gt2martgcex.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gt2jxwfcwpm.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gt2weagwfww.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvknsuim.html

[S41] C++：类与构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2xbpbdnco.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gt2uxsmboub.html

[S42] C++：继承与虚函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2raoqpfzz.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqdpzgwd.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gt2sbghqsne.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gt2jylmzizl.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfejqwfj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzowsjla.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gt2tzcirsfr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gt2zbyekxej.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gt2lpcobuny.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gt2chzhmdjg.html

[S47] C++：结构化绑定遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2ryovhjrz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gt2mnllaqjr.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2tutjntht.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gt2kapjcrdi.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gt2zftzerxs.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gt2fldrrxbl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gt2efgwamaz.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmivodto.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2gnksryxf.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gt2swscybuh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qmncupkt.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gt2zimkmzsq.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdpynunj.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqthwddj.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gt2hecoisjd.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gt2cntgcosf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gt2aronqetl.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gt2qmohtspi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgrsylyj.html

[S56] C++：optional
来源：http://dali.xuanzx.com/Article/details/gt2pjwwplyz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gt2pjvxmcpl.html

[S57] C++：编译期常量
来源：http://dali.c1oappe.top/Article/details/gt2hxvbrfqp.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgkvpivo.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gt2yoxcacio.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gt2ockiriwj.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gt2htfevftl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gt2bektpnqp.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gt2klpdpnfj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cheryme.top/Article/details/gt2vgakqegg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ckztyrfn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gt2dyxjafia.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ibxwdkfw.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2tjibsays.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gt2kguikqwf.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gt2slfmutze.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ealphxjt.html

[T03] Kotlin：字符串模板
来源：http://dali.jlsjyb.cn/Article/details/gt2bvqrjjhv.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvcejuod.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gt2bnhbyhkv.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gt2prioshcl.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gt2fbectpws.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gt2efxikkui.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gt2slleaefi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2cdbodccm.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gt2buglzvpe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gt2sddbxatl.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gt2oxdahsdh.html

data class User(val name: String, val age: Int)
来源：http://dali.yonumen.top/Article/details/gt2nbwxyrqd.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gt2utaivyam.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gt2ungpesgw.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gt2wkfyyuuw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gt2qixynhpj.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gt2pbxwaddr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gt2vtispozo.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqxifgcg.html

val (a, b) = Pair(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2tonlusky.html

[T13] Kotlin：只读 Map
来源：http://dali.9152youxi.cn/Article/details/gt2tbhgocko.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gt2bivhotro.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gt2dnfqmurb.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gt2bhbolawq.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gt2kgjgttkl.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gt2edhnlhgo.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uazqhtvw.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbwvahgl.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gt2oakwrhld.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gt2hefqbnbt.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2xelbnfmr.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gt2smfcjmun.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gt2xnkrtyps.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gt2kkwmvomn.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gt2mexyavcz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gt2fwwvuwrq.html


<!-- 参考信息 -->