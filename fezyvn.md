代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmgxxbc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2amfoetvd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xamovket.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgliwph.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2svjhfius.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvrxzqh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zehupipx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ekridscx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juoqgpjx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlcvwzw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arhlahch.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2asunbihj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xizpqbho.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hmytvxqf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zehkgwmy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsdnlub.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uonznbmq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ullvwgqj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaygnon.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dabvpawt.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfqxlrb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2akvsiaih.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2budzhwbp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbvscsq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2largrlux.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkivfyj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2khbtuqak.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxcrdsw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pinyfcbn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cunvoxga.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyzbgtd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aptfgint.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gifezxpr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pekzxoqi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wkweaetz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxigeey.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyrjczm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jyagxpdt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwvkjxh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiffqto.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsrjfuh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kzldmncm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2adxkggut.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lidastwo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzevkwv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dhahdmwy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhcwxex.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpwtlzh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2syosqfbd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmrvdxo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhwpvcm.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgecktc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lwphzbkd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewugptze.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2svmkvzfn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqpjmlz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxrqlxc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsrmseh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnioctt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2timbqzop.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjqqzye.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkhsowk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ezufjjts.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nwagbsfu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2etohwcfe.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaadgjz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ygofaqtu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2spduprke.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmbbtht.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmgtuof.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtcyusb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2irojkcdx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mtryavkj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjcskjf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtqhukd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lkijrxpu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeywlzm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wcukiyov.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoomekp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2thezranw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2owampljn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlnxcqf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iywxghkj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2caensnyz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcttyjf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkdwdjz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkpuatw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iiczfhlv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxqimfe.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdpnbxs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjmonex.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqqgvaw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2stqqovzq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hcawcrko.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqanfnp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmkzuhv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyizhue.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytummrqt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lupkoaik.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdsvfde.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsielgg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjhsxhw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwoqdzl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wswtfxgp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nzspafer.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2szlzvqis.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xkukwuhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ledhibfd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuffqmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vuchhxwr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2otqvrwxz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2itrjnxld.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxjinww.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ixudabbe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2djzlqrmb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2llhzeump.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgikxfjs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2amowplut.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjmrlnu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbwfzrx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjojkiw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2romhnovi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsipqjz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqwokze.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2swdmfnlt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaaboll.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2iougilhd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qddxdhhe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2frtrxeif.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ipytaucs.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hswydqhd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tphyvzva.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsexvzh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndleqmpy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbilbbri.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaxzoow.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbondtdo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2shigtdsa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ltypzqjh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgbwrss.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsksynh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fjazonnl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hcajzyyy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uigeusxe.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmusojbn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhweyjf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeyeiwt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcqjoic.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzabotay.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rsefcbpw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcsdknq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cndyornc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzktpssn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyqwgje.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwyrvel.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2srymefqy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2avztitkl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrpfpbm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrxchyq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcwvopk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwiefcn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nasobgtz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjuukbr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxduvwq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsikvgs.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aokpnozp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdkellp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyexbkm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhhexgx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntystrho.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2esvcmksb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wusbelku.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rajltgbz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvcjbtm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2veaeelct.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjojngn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqtjbnp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmksofiz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iftnoecq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2auubsouf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqzbszp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dthawmrg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zqelkpqh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnhktmt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzcplcs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkifmigm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnqenbs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zclivjwo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbemlmh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oouoheuz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlxfnfx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qexzufbq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ghevfxgt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrphawu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlutanc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uccwrsaw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnnsfzw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhoouty.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgokttab.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lpydkiev.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dowmqusl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpijwto.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwwnktl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgukembg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpemzcs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmoahle.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhanone.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjfnfrx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvctztm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chvyxnhy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtovntv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjdwocs.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkpxwkn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sotumbdt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ailnweeh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrblvun.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2grcbpazd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdcaymh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2thrwwcpw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2llbceveo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwpdhvt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzqwqdy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbvfajd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzfdinr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjvdpaw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dqslgkhg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbnirql.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcnucfd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nejykdfq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2duqlzneh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlopdxkc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwntndw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnekgeg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iggttoul.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xarrgtoq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qctlrfhu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2snpeupdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmivodov.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qplpcgap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omkywpis.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qckymfeu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2epyjjncw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2halnqvjh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2enfjchjy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2momdmxxp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rndywdzh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uijvdgue.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgjaydh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdilhoi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaylebj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2drowijhl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrimvlpj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2clequwve.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwtwuqq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qmccujtk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbkjvzw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxsurzs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbauual.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2symfkxnx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovojorbl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vydumxbn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzsvbtw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsdotij.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zalgriow.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hatkcshn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yejzdvpv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eplwroly.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuixbbm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsebwjk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfxdotp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2peuinyib.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhsggfg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aegmcbsi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqyimdd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtfarnn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmlomfq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpuoghl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvrxbob.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oygkguzs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gamutbuj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmequep.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pctlhpyp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bokwtlaz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ioacitgh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggciednd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkpmbam.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uthrlnpp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2higkojyn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkgiszl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtinwfxo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcduqwg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qncnvkck.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rimxmwud.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pizxvmvi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2memopmko.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrgmvbs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2adguwpia.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2glhyrykp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2usvozfkb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ourobxnv.html


<!-- 参考信息 -->