代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gt2qgypzdfb.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxnpqnfr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gt2ytryoyuz.html

[R25] 去后缀 / 去前缀
来源：http://dali.havefunace.top/Article/details/gt2fesnlpwc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gt2qfnvylme.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gt2yzxylteg.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gt2niqvrjxe.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gt2ikijmkeu.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gt2hojvyrms.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gt2teyapqqt.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gt2gxojokqy.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gt2hxgisqkt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.meibo888.top/Article/details/gt2pylntsgb.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gt2lrytdkan.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgfjaize.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gt2kkevxvvy.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gt2kqpapcod.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gt2qgzafhdj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gt2iqubnxxj.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vziubfsd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gt2rylulzit.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gt2kjkxaalh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2vvzyctax.html

[R35] 后台执行并等待
来源：http://dali.chenlongwang.top/Article/details/gt2ulupuyzq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2inpiuruo.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qugruwbv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gt2ubvtzdjo.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gt2vctmfrab.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gt2jgmguyud.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfwzyocr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gt2gsgeyknk.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itrbcjzu.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gt2phkvpcks.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gt2cdowrrya.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gt2zpllrdwm.html

[R41] 丢弃输出
来源：http://dali.guowangkeji.top/Article/details/gt2tlqvlemh.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhpncjsr.html

[R42] 输入重定向
来源：http://dali.jqgfzy.top/Article/details/gt2kovyzvyp.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gt2ezmkazml.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gt2npqpvcvx.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gt2fdjxvyxa.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gt2vozurijv.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gt2ccwfkszt.html

[R45] 批量删除
来源：http://dali.tanke756.top/Article/details/gt2yogjibig.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gt2yhuzxuis.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gt2awslfchk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gt2gslcsaqg.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2pveznage.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2oomyjmdb.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gt2hqdcnxuv.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2uuuvbyyt.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjsppwkh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gt2cbzrcbqe.html

[R50] awk 求和
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahlvcrcn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahepbxep.html

[R51] 排序去重取前几
来源：http://dali.nanxinkj.top/Article/details/gt2aijwcnvc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gt2bxerqixk.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gt2ivmctbpt.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gt2wxxpnwzx.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gt2gzjlvich.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ivvv.top/Article/details/gt2wfjtyzkd.html

[R54] 比较两个文件
来源：http://dali.smart0.xyz/Article/details/gt2lbqhcjsm.html

diff a.txt b.txt
来源：http://dali.mhx1999.top/Article/details/gt2mtjcezkl.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gt2swxwtogf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqvihqbc.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojkmrndg.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gt2piehgoyi.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gt2jkzbinod.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzfxlmiu.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gt2ycsxkknb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gt2pdikxktq.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2muauzvpo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gt2crqcnqjn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlhkybbp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258888.top/Article/details/gt2akiftrhp.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gt2vpxrhbcf.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwaivcjx.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilnnheuk.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gt2tlyskrhl.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxwcypkm.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gt2umawcpbi.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gt2zqimiesm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gt2mhcdzkrs.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gt2zvrimuok.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gt2jpkcuntm.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gt2iojlpmdj.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2xustsega.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gt2uqlyiwtu.html

openssl rand -hex 16
来源：http://dali.xuetiantiany.cn/Article/details/gt2lduvatjy.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gt2xiialbec.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2mtyqhsml.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eznvlatc.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gt2mnysgekr.html

[R70] 时间戳与互转
来源：http://dali.bjfxy.top/Article/details/gt2fdugcdtf.html

date +%s;  date -d @1700000000
来源：http://dali.c1oappe.top/Article/details/gt2xnesoxoc.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxyahsbr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yueranfly.top/Article/details/gt2dwmuqhmu.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gt2qxerwtaq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gt2jocmmzbd.html

[R73] 分割大日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2xlbjbjnv.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gt2sjzxbifn.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gt2fhadmqsf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daria6918.cn/Article/details/gt2bwytmfgq.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2ouzlycph.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gt2pntjikkc.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gt2ratfjuvo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gt2xaggruox.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gt2tmirplig.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpszxrev.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gt2ayzazlks.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.bjfxy.top/Article/details/gt2raowfawt.html

[R79] 解析命令行选项
来源：http://dali.redwolf501.top/Article/details/gt2uwpsocko.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gt2mklymzhd.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxiiqmwe.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gt2ymsvscsf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2zfoumfva.html

S. C / C++ 专题
来源：http://dali.chenzaomai.com/Article/details/gt2qjlbguzb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2tfmixgwu.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2nrsooymw.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gt2kkzlyfia.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gt2vjahbpmz.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gt2wzoglrqp.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gt2nzfkuino.html

[S03] C：读入整数
来源：http://dali.iojbl.cn/Article/details/gt2kxbotznw.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gt2dtgtlgmd.html

[S04] C：字符串复制
来源：http://dali.sufxvd.cn/Article/details/gt2iqzeggao.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gt2lxcnlbrs.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcmywpjs.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2igqxnmsn.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rholzduq.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gt2mpxieotw.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbjuzdcy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxinjtqa.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gt2xycjuynb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gt2qshelqoa.html

[S09] C：结构体定义与初始化
来源：http://dali.shuidangran.top/Article/details/gt2jiboowyn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gt2pnkmlihi.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gt2aulmydpq.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bboxdsey.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2kggwqvca.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gt2evuypzne.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2knbkmqom.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2oltvubzt.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2tygbrrzw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gt2fgnptpwh.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gt2zazicveg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gt2zaxcsaec.html

[S14] C：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjzwxukz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gt2rkbtwmls.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gt2ylsqcdgb.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gt2hjpjhtcu.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gt2uvbcovyq.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2eemyvcmu.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2iygeitrp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gt2ucfyjmke.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gt2donhrnuc.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gt2gqrulwqp.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gt2amgnxgrt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2wlaccpym.html

[S20] C：二分查找
来源：http://dali.guannengcc.top/Article/details/gt2mkdbsnul.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2qrhilvqw.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gt2pxvgnsni.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gt2rchptbgx.html

[S22] C：字符串转数字
来源：http://dali.yj20258888.top/Article/details/gt2kuhugvrj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gt2igjqpvel.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gt2iyqwkywq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gt2ovsynsda.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gt2xjhfjitl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gt2gbeceiua.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2dnkfdsrw.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gt2wccdgoka.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gt2honbwgtz.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gt2cfgrrfxw.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gt2ysmxbkpd.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2gkyizszh.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gt2msvagfgy.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwjlrfqn.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gt2vorxwrrd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gt2viybugrz.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gt2sgfndazv.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gt2dwhqilvi.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gt2sizpfxvw.html

#endif
来源：http://dali.daria6918.cn/Article/details/gt2ueibekzy.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2nkqsurvy.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gt2ilyhwgzi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gt2trdnrpgl.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gt2wycxzzgu.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gt2bkttuqvt.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gt2poxryfwi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwwucgyj.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqdprksd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gt2zhffleli.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gt2mpuikqey.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2wtkxlnsm.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gt2bmxcjjue.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gt2rophhojj.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gt2vkvnxhmj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gt2bpxfcbzb.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gt2vuggcobi.html

std::sort(v.begin(), v.end());
来源：http://dali.hysaishi.cn/Article/details/gt2wfqljtmw.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmahqius.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gt2eukqbwot.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gt2lebqpzea.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gt2rkosawbs.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gt2cgjkzyjz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxnxidtd.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gt2bzufstux.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gt2opwrytge.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gt2cflcqmta.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gt2cvspkqgh.html

[S44] C++：引用传参
来源：http://dali.nwbrower.top/Article/details/gt2buqgudvg.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gt2zjvdeflc.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uuygqyzz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gt2xwyhpvpm.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gt2zwzhipcx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gt2ryntdkqs.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gt2dcccpxuu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gt2iaoskapd.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2lrxgjawj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.iojbl.cn/Article/details/gt2ygqniypz.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gt2ixmucfqa.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gt2zgyqleqs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gt2njwinhtn.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gt2edjydmdq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tpuicwlk.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gt2xrqshdjq.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gt2jgpiotbc.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gt2mcxrsytm.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gt2nybplpsv.html

[S53] C++：移动语义
来源：http://dali.shangyingyoupin.top/Article/details/gt2gogqejdy.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktdoijjf.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gt2nfbyvuas.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gt2drktjbiy.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gt2vegyiiln.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2upcwguvz.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gt2daneivqs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gt2yojmwxld.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqrppssv.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gt2qukqnjjx.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gt2xjnbvnpi.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2tqsedxjs.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gt2bbtqhtqi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gt2olcjnflc.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gt2chpuypfh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gt2qhjbrguy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2aalczmqy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gt2nrmsntzz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2bfizoyjf.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2kgfolsuf.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2wtctxsqi.html

[T02] Kotlin：变量
来源：http://dali.yj202588.top/Article/details/gt2ggnjkxpt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gt2rsmlfyyc.html

[T03] Kotlin：字符串模板
来源：http://dali.yongpay.top/Article/details/gt2qpyacoie.html

"值: $b"
来源：http://dali.c1oappe.top/Article/details/gt2qvccthyg.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gt2xiirfefo.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gt2svvjvkiz.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gt2bmwekytt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gt2bwxggogi.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2rwbiylfg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2mueislyl.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2tfrcnsno.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gt2lulzjqmh.html

[T08] Kotlin：数据类
来源：http://dali.sweek.top/Article/details/gt2xgfxhrll.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gt2aejdtjeo.html

[T09] Kotlin：扩展函数
来源：http://dali.xinyue.icu/Article/details/gt2awrisfyb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gt2zarwdxlu.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gt2ggafxgfw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gt2tlxsktxk.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqgdbzst.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cashguo.top/Article/details/gt2kbtxczmb.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gt2lxpkkgpc.html

val (a, b) = Pair(1, 2)
来源：http://dali.tanke756.top/Article/details/gt2heibqtbm.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2buwrargp.html

val m = mapOf("a" to 1)
来源：http://dali.cheryme.top/Article/details/gt2vssuhmjk.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gt2hwvxgpfq.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gt2huidzhus.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gt2zzzdlzrg.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gt2tqacfpwh.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2soufgpfc.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2dcpfridu.html

[T17] Swift：变量与常量
来源：http://dali.gzhubu.top/Article/details/gt2cxkoxevl.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gt2tnlbwatp.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gt2antqjkjo.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gt2udaksjtk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zllvvzbc.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gt2twdwovye.html

[T20] Swift：数组操作
来源：http://dali.hnxiangtu.top/Article/details/gt2jzewwkud.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gt2bmijovnq.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gt2rotvctsd.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gt2taxijesq.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gt2yjafruja.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gogol.net.cn/Article/details/gt2xalcsjgs.html

[T23] Swift：函数
来源：http://dali.chenlongwang.top/Article/details/gt2vwaeyoyf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tian-w.cn/Article/details/gt2wzlfgrhz.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gt2hrzvfhiw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2uhcdyklf.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gt2jghpboxv.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gt2qrgzdybh.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gt2jzcsxipc.html

class A: Base { override func f() {} }
来源：http://dali.zhongyouzk.top/Article/details/gt2kkenwvhi.html


<!-- 参考信息 -->