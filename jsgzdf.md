代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gt2mfigqkji.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gt2kpowiomc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.redwolf501.top/Article/details/gt2btxegdmf.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gt2ahcpfwgo.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2yoowomci.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gt2csnrjobx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.birdmap.top/Article/details/gt2whvblxik.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2fcqzguep.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gt2iwldisve.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvxjxkno.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gt2ahgclpag.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2wrfgkczb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gt2prhunzmn.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2ggmbmbmr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258888.top/Article/details/gt2rqsvmnrw.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gt2vfdotdrw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slgoanbe.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkuwsjzz.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gt2nijmyanc.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gt2aftsmfff.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdmhrpur.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gt2twakfvdy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlsiuizf.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gt2sdlvfsym.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gt2seexadnu.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gt2vrzmjakh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gt2zfkkvaab.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gt2ezigndem.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gt2pfdaeihg.html

[R32] 参数个数校验
来源：http://dali.dashuyun.cn/Article/details/gt2pqhnoysb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hruwiwbh.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gt2lwiupdga.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gt2wxmwdjpo.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gt2hshqijkj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gt2rmvabway.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gt2bingwqsq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gt2ischbmpg.html

[R36] 并发执行多个任务
来源：http://dali.yongpay.top/Article/details/gt2oltyolgq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigufen.top/Article/details/gt2omiaphxf.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gt2qcwekwuu.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gt2eswourtm.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gt2lncisetf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gt2fqxinuxh.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gt2isxniqpx.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gt2fossjnzp.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsjzmlqt.html

echo "log" >> out.log
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbwjrvjo.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gt2akujinsa.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gt2fvjgwvef.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gt2zaagwfdu.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2rbkbvfif.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gt2iyafrjga.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gt2tydmdpxv.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkmhafuf.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gt2bkqjiamc.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gt2tyezpaab.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gt2gvzrvpmb.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gt2jwvmhcwb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhpqwnpa.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gt2zastzfen.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2rqnhqpox.html

[R48] awk 取指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2vveoawmj.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2qjmesliv.html

[R49] awk 带条件
来源：http://dali.ivvv.top/Article/details/gt2ucxtbwaq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gt2vrthxyed.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gt2upqyhbtr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2smxkttzt.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gt2gjpkzaim.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shzxlz.cn/Article/details/gt2afkoyexn.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgghorue.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2vuqxrcty.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gt2llqkwkvf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gt2wwjwwvpk.html

[R54] 比较两个文件
来源：http://dali.kuanghao11.cn/Article/details/gt2tzrlwxvh.html

diff a.txt b.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdjywutq.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gt2hiifgecz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gt2nyoermyf.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gt2xaktcwpo.html

scp file user@host:/path/
来源：http://dali.haohaochexian.top/Article/details/gt2hlvqnaxx.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gt2ahwrychx.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gt2ohcgqdwm.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gt2dyhpnjrp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigfzy.top/Article/details/gt2ygjyalxh.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gt2ngbfekkn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gt2nyrgfrxf.html

[R60] 只看 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gt2ggayavnc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gt2jfyxtkde.html

[R61] 磁盘占用
来源：http://dali.yueranfly.top/Article/details/gt2klphmqos.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epdbawxp.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gt2wvxqycjr.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gt2rnehufal.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gt2ziabnatc.html

free -h;  ps aux | grep nginx
来源：http://dali.daria6918.cn/Article/details/gt2bkahqfgh.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gt2gwsbrdrn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gt2aipgrfuo.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gt2cydjxlaj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gt2irylsszh.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gt2gacazqtx.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gt2nfegqubu.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gt2yulqszwj.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gt2unsamdab.html

[R68] 计算文件校验值
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlkmxjfz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gt2cpfkxtta.html

[R69] 生成随机密码
来源：http://dali.zhengqikj.top/Article/details/gt2gmjkbnkz.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gt2zjkaqole.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gt2tgeqeyla.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gt2ybcpqhig.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2ojdlfcul.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gt2duaihwdx.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gt2wazkcvql.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gt2erzgkjrx.html

[R73] 分割大日志
来源：http://dali.yj20258888.top/Article/details/gt2hkanvgdz.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gt2iweggrdc.html

[R74] 批量重命名
来源：http://dali.zdqjudy.top/Article/details/gt2ooetiklz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daxiang520.top/Article/details/gt2tbxlgrxl.html

[R75] 导出环境变量
来源：http://dali.chenzaomai.com/Article/details/gt2noaijbtl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gt2uulyzfui.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gt2wkqygnpw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gt2robouxhx.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gt2wjpcdomk.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gt2apzbqqst.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gt2trilwkyc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gt2uqpvwyji.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmygpvaw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gt2poybljiu.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gt2tlyqfpad.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gt2ueroqbhi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2kyhbhfim.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gt2zouieyrd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2deqhqhvo.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gt2jnsygnpu.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gt2gulcacvm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gt2ejvyqeag.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2opmldhdf.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gt2xgeritcl.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gt2lqgpzclm.html

int x; scanf("%d", &x);
来源：http://dali.jqgfzy.top/Article/details/gt2bcutlbca.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cptjjzra.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gt2bknrqdhf.html

[S05] C：字符串长度
来源：http://dali.chenlongwang.top/Article/details/gt2znuxuuyk.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gt2lonpywra.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyhayapb.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gt2eqnzxgep.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gt2akowmouf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gt2iwwsrzfi.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gt2pnoilacf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gaohongyu789.top/Article/details/gt2simmlagf.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gt2gsedhoyf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sxryk.cn/Article/details/gt2dblnvgdl.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gt2cvabexoo.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gt2coybqzjj.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2ufuxbtki.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gt2gywozfew.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gt2izycynvq.html

fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gt2lgxwlvxh.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2fmmsodbj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oyxwbwkj.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gt2qupmihau.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gt2shawchkb.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gt2umfczqvd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gt2phxrtwhs.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrvvtuxq.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2aobbbzda.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gt2lxpkwlpy.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gt2fhvztahe.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2zpqggrha.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj202588.top/Article/details/gt2dfdalmcx.html

[S18] C：命令行参数
来源：http://dali.zdqjudy.top/Article/details/gt2qgckluat.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gt2nmvfkqfs.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sebtzdbj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2quwpywyx.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozezugvt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfafahoo.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gt2flnqfbcn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcrxxwxe.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibkytfam.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gt2awvztjxp.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gt2obwbyffn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gt2jafbbhpy.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wvxszcvi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gt2geljzzmn.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gt2lbttjbwr.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gt2zrcwdnbj.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gt2tlkqloof.html

memset(a, 0, sizeof a);
来源：http://dali.aibaodan.cn/Article/details/gt2jndyygah.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gt2oyycnjsq.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2knagszrw.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2byizkwis.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ruhnmuwy.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2dujbbamw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gt2ccforicn.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gt2znmryadp.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gt2opmepacl.html

#define X_H
来源：http://dali.sweek.top/Article/details/gt2yhnmdqww.html

#endif
来源：http://dali.aizwys.cn/Article/details/gt2yexlbwtc.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2wojywvfp.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gt2vocpcpoa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2viicmlxc.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gt2vwtatphb.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gt2iylfcbrr.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gt2saefpiav.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gt2dybnxnvz.html

[S34] C++：遍历 vector
来源：http://dali.snrcjt.cn/Article/details/gt2gjziaowv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gt2wdswrmiv.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gt2sxekjajd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2inlcbghf.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gt2tinljmyf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2jlddhanv.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gt2vibgaoln.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gt2xppiosdr.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbazfwdx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2mzfsqccm.html

[S39] C++：自定义比较器排序
来源：http://dali.havefunace.top/Article/details/gt2cfkumrwe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gt2tgpyjfqd.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2cpmltjps.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2msmtucsf.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gt2ithomkii.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gt2mgtwsezi.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gt2zwndhtno.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gt2ldnapibk.html

[S43] C++：智能指针
来源：http://dali.hnqzz.top/Article/details/gt2kncrbymh.html

auto p = std::make_unique<int>(5);
来源：http://dali.xziqi.cn/Article/details/gt2dloqrqsr.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gt2qupstetu.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gt2xyyumjim.html

[S45] C++：lambda
来源：http://dali.yuanzhike.top/Article/details/gt2vldblzzc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gt2sdibzgql.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gt2aljhzsvv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gt2vjohngrn.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gt2irprkdje.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2furozfoz.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2odmchrai.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gt2gdoojodw.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gt2raetmhxb.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gt2bpnzclkn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gt2vwnjwonq.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gt2avwvbrxp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2zgejlgnf.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gt2vlvwetts.html

static_cast<double>(a) / b
来源：http://dali.ppjwa.cn/Article/details/gt2nedwhmdd.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gt2elhiexyd.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gt2fsexisuc.html

[S53] C++：移动语义
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhxtrimu.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gt2jivdpxpp.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gt2dsvbktdt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ivvv.top/Article/details/gt2cdadihup.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gt2ndkpxtvj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gt2bmwtqhou.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gt2drcnaagx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvldubec.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gt2elwifupx.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gt2onqpheho.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gt2llzocfop.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gt2dooimivb.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gt2dgsonixi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj202588.top/Article/details/gt2dwehpsol.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gt2qrcbsiqc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gt2idsjlbhp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wcleeyhm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gt2zgtatmsp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ezldvpbx.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2ykoxuhiw.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2ceigurhm.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gt2svukbcrh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gt2usesggbr.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gt2qshesyis.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gt2judaanzj.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgesblop.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gt2qozzjyfw.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gt2orcbhsls.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gt2kkoyiymw.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2fsdfsbqk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpeqxxqo.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2kiyxabxh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlgvsbbg.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2masvdpgy.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gt2bjcxlmgh.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gt2ervxhnef.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oaneydbn.html

[T10] Kotlin：默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2giwvayjk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilgwwozy.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gt2huutjvbn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.svipenyu.cn/Article/details/gt2fbrpibwo.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigufen.top/Article/details/gt2sisuobba.html

val (a, b) = Pair(1, 2)
来源：http://dali.pycfn.com/Article/details/gt2ezbfjvrs.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gt2jfhbllev.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gt2ojxfuvwa.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htlpymcl.html

for (i in 1..10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gt2hdqnzahd.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gt2mbeizrzi.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gt2llsqaqhv.html

[T16] Swift：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2zvxaqfab.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2ioqtwcrg.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gt2sdintnqd.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2upmpzscx.html

[T18] Swift：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2qbyqynzt.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gt2plupgcgv.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gt2qtmzratf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkykduu.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gt2ctqsyacq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gt2zcegmttr.html


<!-- 参考信息 -->