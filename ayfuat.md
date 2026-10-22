代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wixfybxt.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gt2lzhobezm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gt2aqlxwmrr.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gt2vzbjclnx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgphpmkz.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gt2cxpqspwn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gt2fupuzdbv.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gt2kracsywl.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qmxjwmgo.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gt2wastphof.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjahjgqb.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gt2vczvyoaz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gt2cgyttrhl.html

[R34] 退出时清理
来源：http://dali.guowangkeji.top/Article/details/gt2bgfvdpig.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gt2vwxrzrgp.html

[R35] 后台执行并等待
来源：http://dali.yj202588.top/Article/details/gt2qbptglps.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gt2akskjgre.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gt2wodewgtt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gt2impbtzvz.html

[R37] 把输出赋给变量
来源：http://dali.nanxinkj.top/Article/details/gt2qwxkhcvd.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2jfhnjcre.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gt2njalxzqb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hysaishi.cn/Article/details/gt2nhwibtqb.html

[R39] 重定向标准输出与错误
来源：http://dali.yj202588.top/Article/details/gt2ihydqmfp.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gt2cegpgbnp.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gt2kmmqdbyz.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gt2zgxsvbhn.html

[R41] 丢弃输出
来源：http://dali.zdqjudy.top/Article/details/gt2kygxncmz.html

cmd >/dev/null 2>&1
来源：http://dali.yongpay.top/Article/details/gt2mscbrekx.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gt2qzpowxet.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gt2dagshwyz.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gt2niotwpsk.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gt2xniiuien.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gt2kxdponsz.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gt2smrrbtwx.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gt2swwsgtvw.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gt2kndhcokh.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gt2frhxrkws.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gt2cwetqqal.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gt2qxgpxwmj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2nscvfxid.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gt2cimwxqvl.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2tsyjdukf.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gt2gohvtogc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gt2idhdwrof.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gt2bprpzheq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2vmxsahwt.html

[R51] 排序去重取前几
来源：http://dali.c1oappe.top/Article/details/gt2untrfjqh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gt2ineaugqr.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gt2jsmtkokh.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2owcwzfzl.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gt2apeoluvg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sxryk.cn/Article/details/gt2badbnngv.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gt2meveibfp.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2kewxfaec.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gt2daefajer.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gt2hgbasjov.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gt2byrkqnln.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gt2brcbttge.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2styglhho.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gt2eyqntenh.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mcnrhkow.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eawqjsxp.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gt2efgkxdtb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gt2eddsnoav.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gt2yrdfksit.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gt2dvsbjqyb.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gt2kypjqrup.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gt2qphpoynu.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gt2ttarplnq.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258.top/Article/details/gt2uwwefsbt.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gt2ikgtfwdd.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gt2omesffuh.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gt2qilghkpr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gt2qqqvmxnr.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gt2mgwkusql.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gt2dnfjbwvj.html

[R66] 定时任务
来源：http://dali.bjfxy.top/Article/details/gt2zuyfethc.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gt2crwzyzin.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gt2ldvpsvih.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gt2zsaollyc.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gt2gqcjapji.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2jbshrpuj.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gt2mpdjlfvz.html

head -c 16 /dev/urandom | base64
来源：http://dali.yongpay.top/Article/details/gt2nbyxykbe.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gt2xctaumcn.html

date +%s;  date -d @1700000000
来源：http://dali.shzxlz.cn/Article/details/gt2toilwabl.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iyhfwxcs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gt2iwyobuht.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gt2wkpijzud.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gt2icwngweh.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gt2alahuyym.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gt2kgzvsweb.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gt2aruktohd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guowangkeji.top/Article/details/gt2ccofpmlr.html

[R75] 导出环境变量
来源：http://dali.jqgufenzy.top/Article/details/gt2ghznuwvp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gt2qwzzncte.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gt2musgechy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gt2hlkegrzs.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gt2nbosdpjj.html

read -rp "请输入: " ans
来源：http://dali.yuxming.cn/Article/details/gt2flkbxnzo.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gt2srwnpomn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gt2hhxrhvoc.html

[R79] 解析命令行选项
来源：http://dali.andypj.xyz/Article/details/gt2kksmuyav.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gt2ejqviqwg.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gt2xrquhiaq.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gt2ftvjhpke.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2lyviupwj.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gt2jlxpwgnj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2jkxkqozh.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2aipoxlwh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fczwfbbb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gt2npryamfj.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gt2jvibptft.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gt2dbbddzwf.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gt2ebikyfwk.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gt2znhtugzi.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gt2yjublcez.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gt2oaqhgicp.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2puknmwxc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksolpxdn.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gt2zkambjvk.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gt2yzcfxiko.html

[S07] C：数组遍历求和
来源：http://dali.cdnleiting.top/Article/details/gt2oolpbrng.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gt2yjlyzhim.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cllzjikt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gt2gfjwterh.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gt2tcagagyk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gt2zqkuiawd.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gt2yogtyqxu.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gt2vppludpa.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2ajjuljir.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gt2umaennky.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2sfigtwnm.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2fyzrsrzh.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2bnnhjctf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gt2xeuryujh.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gt2rhcrgozt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gt2eryjenmo.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gt2tklhtmjo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gt2hyafmlpo.html

[S15] C：类型转换
来源：http://dali.nanxuanxn.top/Article/details/gt2yarcwqzp.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gt2ahsqbntm.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdjaeeph.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2ivtcbeey.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2hnfwaqea.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gt2tvlgvkeg.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2fuisupbk.html

int main(int argc, char **argv)
来源：http://dali.fengsongda.top/Article/details/gt2njfwmzzx.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gt2uqxccint.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gt2gmcoiagw.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gt2ordcidfu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2aidzsxzl.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gt2aaglwewk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gt2nkpmfcjg.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfvgqdbm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gt2ztvftfsf.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gt2dzzmpewn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gt2svsuzjly.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbzuyxfq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gt2ykfgqyij.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2qbwelxis.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gt2rtcrldbc.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gt2fldfkqty.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gt2rzrhpdol.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gt2vspiqzfl.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2qemhfebt.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tuwsbitn.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gt2etuaaxjm.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gt2bsiqpewm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gt2lylvjhdu.html

[S30] C：头文件保护
来源：http://dali.sweek.top/Article/details/gt2kqhyowko.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2wwsvwluz.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gt2hkvxhzrn.html

#endif
来源：http://dali.nwbrower.top/Article/details/gt2jtbfhadr.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2xyvxmsca.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gt2tmtjchwb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gt2yyqhirwg.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gt2ufsvplro.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gt2mspfgwwx.html

[S33] C++：vector 增删
来源：http://dali.fengsongda.top/Article/details/gt2btyqopfz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gt2rhndllts.html

[S34] C++：遍历 vector
来源：http://dali.zhixingplan.top/Article/details/gt2cdiepajn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gt2agdlgifq.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gt2mhozfqig.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2vfxfvfpv.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gt2sjrstoob.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2cqcdiovj.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gt2lroflbwv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gt2eybjpztg.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gt2ninuuegq.html

std::sort(v.begin(), v.end());
来源：http://dali.nwbrower.top/Article/details/gt2kdwlgowj.html

[S39] C++：自定义比较器排序
来源：http://dali.c1oappe.top/Article/details/gt2fzqqurjt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvcfqbsc.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gt2pnpjslxw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gt2flvssgat.html

[S41] C++：类与构造函数
来源：http://dali.ydzc1.top/Article/details/gt2xzujwyjd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gt2gjxnlues.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gt2wuikkezh.html

class B : public Base { public: void f() override {} };
来源：http://dali.gogol.net.cn/Article/details/gt2fqbbooyf.html

[S43] C++：智能指针
来源：http://dali.guowangkeji.top/Article/details/gt2nohlfyoo.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gt2qfmjaclm.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gt2qianeabz.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gt2gxurcxkc.html

[S45] C++：lambda
来源：http://dali.sufxvd.cn/Article/details/gt2oxjsavsa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gt2gzddyrfk.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gt2pmiglrgs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gt2zkhzszby.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gt2gucogzrl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gt2woqloydb.html

[S48] C++：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2eswwgyar.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.iojbl.cn/Article/details/gt2ofeuscgx.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2zcrknkxv.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2dvrtfddq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gt2piayebtt.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gt2jrmcyzwg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2tapxfyhb.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdmtqezj.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gt2hjlivnpf.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gt2nlzixccx.html

int size() const noexcept { return n_; }
来源：http://dali.kuanghao11.cn/Article/details/gt2amkyxqdk.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gt2yruuyolj.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gt2vhojrsqu.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gt2pjjcpufu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gt2yvbtafxl.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gt2ghpsojzx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gt2zesazxns.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gt2muogsedq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gt2uugsriwc.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gt2jkcjggwd.html

constexpr int N = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxepthef.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gt2xsixqoay.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gt2jrofgawu.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gt2bxdmjoqf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gt2giqjfhdl.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gt2dkanceyt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2fpfsmoja.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngiynjma.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gt2lxcvmjra.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2jswctmfg.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2ttrklyst.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2qzcnbnyj.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbqtjvmb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gt2ljlchodk.html

[T03] Kotlin：字符串模板
来源：http://dali.aibaodan.cn/Article/details/gt2fmvfhxqa.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gt2bcvsvrzo.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gt2bwcofpxo.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gt2mcijxhcu.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gt2kykcqfqm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gt2jxxaxnog.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gt2omcxwjnt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2wwawagct.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gt2yubtkbmh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gt2zvykovxm.html

[T08] Kotlin：数据类
来源：http://dali.yanxiufei.cn/Article/details/gt2pwilvljm.html

data class User(val name: String, val age: Int)
来源：http://dali.sweek.top/Article/details/gt2tzmmdpyy.html

[T09] Kotlin：扩展函数
来源：http://dali.jyoumei.cn/Article/details/gt2cxeneste.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbbnsaku.html

[T10] Kotlin：默认参数
来源：http://dali.nwbrower.top/Article/details/gt2wtxyqacw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gt2tchsbopv.html

[T11] Kotlin：协程
来源：http://dali.quarkkingdee.top/Article/details/gt2xqoalxyr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258.top/Article/details/gt2avwrewen.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gt2lotclpvo.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gt2qggfocox.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gt2czcnirsv.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gt2haksvqph.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gt2xnclrfje.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gt2kokbzase.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gt2kxvxjopo.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gt2yfswcudm.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gt2mvavdadj.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2qpaxdogq.html

[T17] Swift：变量与常量
来源：http://dali.cucudq.cn/Article/details/gt2tgaiuvhv.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gt2qwmnovnx.html

[T18] Swift：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oildrcqk.html

"值: \(b)"
来源：http://dali.bjfxy.top/Article/details/gt2sdrbwwyd.html

[T19] Swift：可选绑定
来源：http://dali.guowangkeji.top/Article/details/gt2bujwdhyp.html

if let n = opt { print(n) }
来源：http://dali.zhongyouzk.top/Article/details/gt2anwuxazx.html

[T20] Swift：数组操作
来源：http://dali.jqgufenzy.top/Article/details/gt2idfqcpmd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gt2jpkucqbk.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gt2ukgfjfmm.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcgwjsxr.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2huguadoi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenzaomai.com/Article/details/gt2sneaxctq.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gt2xkdcozkb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.andypj.xyz/Article/details/gt2vyqztlcn.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gt2zsvdmkyj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cashguo.top/Article/details/gt2nbnemfan.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gt2xgkpvthj.html

struct P { var x: Int }
来源：http://dali.sufxvd.cn/Article/details/gt2zsguplyz.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gt2zkaijyrn.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gt2djlmwmlc.html

[T27] Swift：错误处理
来源：http://dali.sysykeji.top/Article/details/gt2igwrqbox.html

do { try f() } catch { print(error) }
来源：http://dali.hnqzz.top/Article/details/gt2qlgroqox.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gt2lynlrfpx.html

enum Color { case red, green }
来源：http://dali.tian-w.cn/Article/details/gt2tqpfroxq.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gt2sokewrhm.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjaipenf.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gt2mkrkzrcu.html

protocol Shape { func area() -> Double }
来源：http://dali.gaohongyu789.top/Article/details/gt2mgwxkcdi.html


<!-- 参考信息 -->