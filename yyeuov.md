代发 wailian999

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtmzgopcwy.html

[R20] 关联数组（字典）
来源：http://dali.gaohongyu789.top/Article/details/gtvxacvrdq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gtbtrbtsuf.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gtspdrppga.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gtyxqygvxm.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozzhtjhk.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gtnscogqdk.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtbwpvmiab.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcowrlfj.html

[R24] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtjcznfkqf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yangfankeji.com/Article/details/gtdupyayag.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtkzmrjsuj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gtmtopckbz.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtjlxpuvxj.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gtdwpewhgs.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtahlmgwql.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupdxwcov.html

[R28] 浮点运算
来源：http://dali.wangshuangyany.cn/Article/details/gtttaxswvy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdaywdinz.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtulcpnzsh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tanke756.top/Article/details/gtbbcxxwih.html

[R30] 函数返回状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtbqielaeg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gtzdpjdkjp.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gtdsvnttac.html

f() { local x=1; echo "$x"; }
来源：http://dali.daria6918.cn/Article/details/gtwtymbetx.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gtavyxznym.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtdimkegyf.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gtrvnknmdl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shuidangran.top/Article/details/gtmrwptxcv.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gtootzyscx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtstnzjfwt.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtqtyflgwd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gtzjiyzasa.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gtvjbeenvq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gtnxcrxngp.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gtzmrvgjkc.html

files=$(ls -1)
来源：http://dali.tianlin.xyz/Article/details/gtukhaguic.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gtvcqhkvwd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtlehbnagu.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtpdevmtla.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gtautyglgk.html

[R40] 追加写日志
来源：http://dali.yanxiufei.cn/Article/details/gtjmmtdfqa.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gtcfbtfhec.html

[R41] 丢弃输出
来源：http://dali.xinyue.icu/Article/details/gthtwcfdof.html

cmd >/dev/null 2>&1
来源：http://dali.gotoacloud.top/Article/details/gthremezlg.html

[R42] 输入重定向
来源：http://dali.shuidangran.top/Article/details/gtgnnmkzeo.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gthurkcotj.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gtsdewzrpi.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gtyxrnoyjz.html

[R44] 按修改时间查找
来源：http://dali.nanxinkj.top/Article/details/gtrjmbadhu.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gtyhzkpqnr.html

[R45] 批量删除
来源：http://dali.jiagoushi.top/Article/details/gtxlufohkz.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtnayiacdz.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gtjmigatjn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gtierntraf.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gtzzojriti.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gtcgsxtfnl.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gthnmimchy.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gtmbpqukbm.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gtyqnjixrf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xylfe.cn/Article/details/gtktnrwnnk.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtcklqlxkp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtsfbgbfbz.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gtatuczazq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gtymckipfe.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gtmfbnancx.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtitmcwcfu.html

[R53] 查看文件头与实时尾
来源：http://dali.gaohongyu789.top/Article/details/gtfdxeefap.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gtegbzpeln.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gtsjfnxwmv.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gtjtafqpkj.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gtxuskqjrs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gtrijlifuw.html

[R56] 远程拷贝
来源：http://dali.yangfankeji.com/Article/details/gtntiewizy.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gtxtkmxdji.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gtsjtnuwbw.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gtpdqxseqo.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gtgpnqfvfn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtittdzhpn.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtmewuywdp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gtkxzicszr.html

[R60] 只看 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvgwjteu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gtucqsqmho.html

[R61] 磁盘占用
来源：http://dali.wangdashe.top/Article/details/gtcsaasaqh.html

df -h;  du -sh *
来源：http://dali.quarkkingdee.top/Article/details/gtxzhqrmkm.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gtejxscwlo.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gtzkhckfyf.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gtatzmnmrp.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gtdlecymdm.html

[R64] 结束进程
来源：http://dali.cqqwz.cn/Article/details/gthtjiivvg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gtitoibzdo.html

[R65] 查看端口占用
来源：http://dali.aibaodan.cn/Article/details/gtdeicsxrv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtohqtspxo.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtnybdjzut.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gtxaultgki.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtnxwidmwv.html

openssl rand -hex 16
来源：http://dali.guannengcc.top/Article/details/gtcrqasuzu.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gtyixnpyud.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gtcwpgunmx.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtacrafyoq.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxuanxn.top/Article/details/gtknisjkig.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gtxwecrivl.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtyicngzrg.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtyhbuhivn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tanke756.top/Article/details/gttpksbdxa.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtgiznacke.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtasmknbnt.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gtxlgjohlj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gtqpcehfan.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gtssffhjxo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gtwhzqcavn.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtlmjxgihq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gtzdrvamli.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtcbhxauyq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtppqsslue.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtlythrmee.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gtitiqicyw.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gtgamaumhi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gtzqttjoft.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtadklozge.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gtqbmbxhww.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gtqpzprblb.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gtfvabbqeb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthhvufgkb.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gtswyqiqwa.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvghuplfq.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiddwefov.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gthrxnktki.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gtzbzhhiej.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtvqawbjtn.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gtqiqatdhz.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtljwywnbk.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtfsezzbvl.html

[S04] C：字符串复制
来源：http://dali.tianlin.xyz/Article/details/gtptctsjbj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtzebjnzbm.html

[S05] C：字符串长度
来源：http://dali.xylfe.cn/Article/details/gtgijkftlk.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gtrgaxmsqu.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gtphdsvvai.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gtyevhruio.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gtlsxnpzpb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.c1oappe.top/Article/details/gtrjuvexfi.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gtpdthbzbs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gtlvamynkj.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gtvohfryre.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ppjwa.cn/Article/details/gtgywidlws.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gtlllpmymh.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gtjansovys.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gttxcpqnwl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gtkemuqxhm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkgmhjlv.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtiggjrixd.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtbzpwmqmh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtxsgxtost.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gtiakjqapd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gtlgmjhnyi.html

[S14] C：枚举
来源：http://dali.bjfxy.top/Article/details/gtcjjibkrv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gtlmjicgzi.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gtqfnltjrg.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gtsznpvgpk.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtnaqkxspd.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gtghkjamsb.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtrsqecuvk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtfixqfgfm.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gteesfbijj.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gtddirzjwk.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtdvrtbsaq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtigmbrwix.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gtxnbdakdf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtbnijjfop.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gtcmbxzkzm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gtldmihtpu.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtjsvyljjn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gtrgvaseez.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtwmbqzntw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtfdeunwoy.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gtkutajckd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jiagoushi.top/Article/details/gthcwvxqew.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtvicorodl.html

memcpy(dst, src, n);
来源：http://dali.hongshengwenyu.top/Article/details/gtqoqfxhbb.html

[S26] C：内存清零
来源：http://dali.pycfn.com/Article/details/gtmscwdmrc.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gtfxajixrv.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gtkbgbljjn.html

const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtqpufaoaj.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtvvgtsmeu.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gttjagwblb.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gtqlemvlzt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gtgifkwhad.html

[S30] C：头文件保护
来源：http://dali.hammf.cn/Article/details/gttkdkwqec.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtfuoconca.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gtnyafkcjt.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gtgkzoijxd.html

[S31] C++：Hello World
来源：http://dali.xuanzx.com/Article/details/gtxtcboblx.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gtktfcsprv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gtfxpmqlkh.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gtgxcfzkkx.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtikppsdxk.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gtovhjqrkr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gtwdnfuzpt.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gtnfqgwyip.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gtooilgapi.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gtdxnxcgbc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtdwqllliy.html

[S36] C++：unordered_map
来源：http://dali.jqgufenzy.top/Article/details/gtnfkxcrez.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtncycdatq.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwovrspq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gtqtbhrlpx.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gtpdyafdjv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtrksyptnd.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtyzbjodga.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtqjildavu.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gtbqvwdmdl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.iojbl.cn/Article/details/gtdhitbscq.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gtkxxmxtpz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtmgzkgwlo.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtejluquor.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyvvaafa.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtvolipbrm.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnzpkzcd.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtkirtjfwp.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtwidsmgxb.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gthrcmcnla.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfktvxvb.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gtlsnentcy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gtqjceaelt.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gtnwskyhaw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpokiysv.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtxnkppciq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jianghu66.top/Article/details/gtkmpgumfs.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gtbgzejzct.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gthhvbhogt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gtnioekhrr.html

[S50] C++：格式化数字
来源：http://dali.jqgufenzy.top/Article/details/gtsgzuhmil.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtzxvfzkyc.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gtsovfezml.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gthjxacodo.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gtuybadalj.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gtdtvcqahu.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtudkfirve.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtnpwsfaum.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gtsmrzlqgh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gtaghwbbtp.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gtjszrfgng.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gtwfnayyxn.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gtipzmubyy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gtdwdvxike.html

[S57] C++：编译期常量
来源：http://dali.andypj.xyz/Article/details/gtfulepwrp.html

constexpr int N = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtznodcfso.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gtivijaked.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtlfqmrciv.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gtqpndvrua.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gtvlciewzr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqjkxwrk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtbtwwvqma.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtclvhnhvo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gtfahsvqsx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbmrilglo.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gtxhvbcdhm.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtieizcjmg.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gtrsysfnlk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gtbumsrdtk.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gtrjoswjtv.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtkeufydcj.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gtgomeemdx.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gtdtgynulv.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gtiezramkc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gttdafrexg.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtcxkmwvie.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtfntqvvyi.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtlmkrgdvt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtalfocowl.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtqwmrqmvy.html

data class User(val name: String, val age: Int)
来源：http://dali.bjfxy.top/Article/details/gtahctksdk.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gtoudmcmyp.html

fun String.exclaim() = this + "!"
来源：http://dali.guannengcc.top/Article/details/gtdxjbhmwf.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258888.top/Article/details/gtmqbismwy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xziqi.cn/Article/details/gtucoicjgf.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gtxqjabtvl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcbrfmur.html

[T12] Kotlin：解构声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkgpmcob.html

val (a, b) = Pair(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtkimpimvm.html

[T13] Kotlin：只读 Map
来源：http://dali.chenjidiqi.icu/Article/details/gthdjdkgoy.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gtvrmoebgr.html

[T14] Kotlin：循环
来源：http://dali.yuanzhike.top/Article/details/gthkgvboik.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtaygjpihm.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gtcgxxqkgh.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gtzcbzcner.html

[T16] Swift：Hello World
来源：http://dali.xinyue.icu/Article/details/gtowvssomv.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtpiovxuon.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtkgljlvie.html

var a = 1;  let b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtlucqiguv.html

[T18] Swift：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtexhjgnli.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gtosuokvez.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gtkucyqlnq.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gtovclhmgt.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtxjebuslj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtutglxnay.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gthsughuhw.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gtifckcpuz.html

[T22] Swift：字典
来源：http://dali.chenlongwang.top/Article/details/gtrogfojzd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sxryk.cn/Article/details/gtifjyblfs.html


<!-- 参考信息 -->