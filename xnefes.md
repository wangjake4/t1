代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.quarkkingdee.top/Article/details/gtjepdjxre.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtznpfollf.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gtvvsvcwic.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gtrxcqcohw.html

echo $((1 + 2 * 3))
来源：http://dali.chenzaomai.com/Article/details/gtbtiwmpvc.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtwlktrfnc.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtvekijwmt.html

[R29] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtbisxgtcg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtgafwhwub.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtoejpoous.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gtpxwqpsxo.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtyqcwktxk.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gtfqtpzdvu.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtorgekklq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtjhewxqfw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gtjnxjcpcd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gtfawqlcjr.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtssksblje.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtjziirfgm.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtgaunorik.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxinkj.top/Article/details/gttduhousg.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gtyblylwmz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gtrdwaxilb.html

[R37] 把输出赋给变量
来源：http://dali.xinyue.icu/Article/details/gtpcwjiaha.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtlkxlewyp.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatpaxytx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gtbzdflnpx.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gthazumits.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtpcnzzsoy.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gtzgwvkfzs.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhmfhigw.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gtpthgdcwg.html

cmd >/dev/null 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtdoslkmit.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gtuymugfxj.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gtzsnspneg.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gtnqmubfbp.html

find . -name "*.log" -type f
来源：http://dali.kuanghao11.cn/Article/details/gtnucykrxw.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gtarahckdb.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gtjinklglg.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtftkayeui.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gtpgmtcpgt.html

[R46] 递归替换文件内容
来源：http://dali.mhx1999.top/Article/details/gtlqfoplla.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gogol.net.cn/Article/details/gtcfsetlzq.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gthoktaifp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtzlpskvus.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gtuxqflzea.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtkpcrihqs.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtxhbjvofy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gtiruqkkdr.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gtmraaafzo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gttfsdvfjn.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtofmrntwu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gthgpkrpdj.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtzundmcig.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gttigonxup.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtpfkvqdnn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtgxzykryp.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbdlydrz.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtsdvrfxax.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gtljycsaxr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gtbdqjrlaj.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpimscik.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gttiudrpxz.html

[R57] 远程执行命令
来源：http://dali.gotoacloud.top/Article/details/gtoxksweki.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtkaylfiir.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gtgucsnozx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtpoadblen.html

[R59] 发 POST JSON
来源：http://dali.yj20258888.top/Article/details/gtdrmwsdyx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gtwhhueagj.html

[R60] 只看 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtmzteljvr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gtgnozdwcb.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gtjnqrhyta.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtfgpnphsm.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtcvsoosnd.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gtojidiptt.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtcwtwcyyu.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gtynxlkuow.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gtutnkpbby.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gtdbzhejzi.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gtmrygcngv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtybciczaa.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gtzzendgcs.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gtrqqmppjp.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtorxkwlfo.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gtkuoxbddp.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gthsymbyuy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gtbbvscshl.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gttjurtevm.html

head -c 16 /dev/urandom | base64
来源：http://dali.iojbl.cn/Article/details/gtjhrmnonq.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtcjfjtbpn.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gtepfifdxr.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmovrisfx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdennhlc.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gtsoontenx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtmhzacsgb.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtvnhhplft.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gtltdlerhd.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gtqxwjzira.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gtipssucqz.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtxnmvsclc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtrhleiwmw.html

[R76] 使用临时文件
来源：http://dali.jianghu66.top/Article/details/gtjfjewcge.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtqhwzmasb.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtbztptuhy.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gtppbvhzth.html

[R78] 交互式菜单
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiyjqmpi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gtxaoycolf.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gtmtcpmbme.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gtlaqnbzmj.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gtxcgirjlz.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gtgalfeosi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtujdvgoqk.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtdstcpduj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsmjwyton.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gtzzsvumne.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtogfbsovc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.c1oappe.top/Article/details/gtuztyzipi.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtjjdlmldh.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gtvlwldukq.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gttehwqqop.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpplpkgp.html

[S04] C：字符串复制
来源：http://dali.ivvv.top/Article/details/gtjewobanr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gtoianynzu.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtxvcjgfim.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtxgzpzlmi.html

[S06] C：字符串比较
来源：http://dali.redwolf501.top/Article/details/gtpoxaoljk.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtuipfymgx.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtrxcgjsvw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gttjzxxcsr.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gtrziygzbx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtvxuqczfi.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gtuhhpfcni.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guannengcc.top/Article/details/gtwvefikke.html

[S10] C：指针与解引用
来源：http://dali.gotoacloud.top/Article/details/gtiqixighi.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gtzgwazbhl.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtazfnprpa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gtfofdimwz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtqhuhysvn.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtrczsrxnz.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gtzzyzlhcg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtkfvllkxd.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtuhdlzgsa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gtwpkyzbwd.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlwbfhdi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gtymcotuwj.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gttdltxzvf.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtqvllcdad.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gtcofaygbk.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gtkijxfzff.html

[S17] C：安全拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtczupxkuo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gtrnmxayme.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gtiajprgbz.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelahbunh.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gtankcchka.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtijjhqcly.html

[S20] C：二分查找
来源：http://dali.jqgufenzy.top/Article/details/gttezdjfys.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkdorwtx.html

[S21] C：字符类别判断
来源：http://dali.chenlongwang.top/Article/details/gtewjxoxiy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gtkextufnv.html

[S22] C：字符串转数字
来源：http://dali.andypj.xyz/Article/details/gtdvrghybz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhoulong.xyz/Article/details/gtasyeclre.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gtwqbadbga.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gtuaddjnye.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gtnxpkbagw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeiapykd.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtmmewbocw.html

memcpy(dst, src, n);
来源：http://dali.daria6918.cn/Article/details/gtunrqyotw.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtpeokmaqc.html

memset(a, 0, sizeof a);
来源：http://dali.zhoulong.xyz/Article/details/gtpsxazkik.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtjirvbews.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtidseqhyw.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gtzofmjwkw.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtmwtohgqd.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgialrvr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gtkdsokoyz.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gttnhnqfzq.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gtvoxormeq.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gtmphpetey.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gtuhggplkm.html

[S31] C++：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtjnfritip.html

#include <iostream>
来源：http://dali.pengpengdd.cyou/Article/details/gtevagrdnh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gtbqhpdsqj.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gtoltlwzis.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gtbznqpjyq.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtdcuizxzq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gtpgwdzmhc.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtdgfpqrbw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gtatcaegup.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gtdtnmqpsw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtblfglkwj.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gtygdmsmay.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtrogweueh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gtdjnqgxsc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtpovqrlau.html

[S38] C++：排序
来源：http://dali.jiagoushi.top/Article/details/gtcuikpuow.html

std::sort(v.begin(), v.end());
来源：http://dali.9152youxi.cn/Article/details/gthoscfhvt.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtxlrdqkcu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gtasnubszg.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtpuijunpy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gtwxztcwdo.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gtgqddcvrn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtebismcvc.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gtqhiisbzz.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtkpjbryeb.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtafuloimk.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtomhcdowu.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gtloghhyud.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gtabiysuxa.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtwkwywahh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gtpocizirn.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhaqztok.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gtevkfvpdv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtlzudtcpb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktlxolcz.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtjkimampc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqdaqcjj.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gthpwiiitn.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtmvtxzetd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gtxukwohxl.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtxsxfwplg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gthsyciqfj.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gteenfuydi.html

static_cast<double>(a) / b
来源：http://dali.yanxiufei.cn/Article/details/gtablepiod.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtjkbiggzu.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gttientutb.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gtjbgkurkz.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gtsrefdmtf.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gtyybtgtey.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gtwkbkhzkp.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gtnbwscrxm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gtywrdbnrm.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gtobwlzllq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gtoxpmywzo.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gtqufjoykh.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gtjlowhxgj.html

[S58] C++：命名空间
来源：http://dali.kuanghao11.cn/Article/details/gthafjyiun.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gtjvqzllsf.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gtgrqvfbvf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtndjjlpsc.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gtulzuwiaz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtsopnriqb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthjhbbbfc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtazrtdaom.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdaausuku.html

[T01] Kotlin：Hello World
来源：http://dali.gzhubu.top/Article/details/gtjhlwzpew.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtzehbfqly.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtbrgplhzw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jiagoushi.top/Article/details/gtbbvqjowl.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtcftprmbb.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtqmzryhod.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gthxmgvbpo.html

val n: String? = null;  n?.length
来源：http://dali.nwbrower.top/Article/details/gtczydsaje.html

[T05] Kotlin：when 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtsbwdtfqp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gtuoenjsfl.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gtvnhwxqva.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtubfzbtoj.html

[T07] Kotlin：集合过滤
来源：http://dali.cashguo.top/Article/details/gtpoggcvra.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gtjlkuezbj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gtitukznys.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gtpeowgkrj.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gtwzrygztc.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gtfoffcwbh.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gtdnnpyzlc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gtscgbwzyd.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gtqvdcxsfk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gtibqnjzva.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmhrkqyj.html

val (a, b) = Pair(1, 2)
来源：http://dali.pycfn.com/Article/details/gtgjgvbvzn.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gtfeatuuku.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcmgulve.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtjkhncwin.html

for (i in 1..10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtzhsihxnc.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gtmbgrnymu.html

interface Shape { fun area(): Double }
来源：http://dali.yonumen.top/Article/details/gtzhmwpkel.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtsmcdsclk.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtxfzyldme.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gtrgpeszbo.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gtxlbrulnp.html

[T18] Swift：字符串插值
来源：http://dali.yj20258.top/Article/details/gtxnyxgaiq.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gthehvyxcn.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gtgbqqtpgv.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtxqptplti.html

[T20] Swift：数组操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscaxuukl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtgiafjebh.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gtbdeiwanq.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtbrpmzpld.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gtdqhltoav.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gtmcchaggf.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gtpnkjnbhv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shuidangran.top/Article/details/gtukqskvzz.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gtaaxckdtp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtlvyshnue.html

[T25] Swift：结构体
来源：http://dali.mhx1999.top/Article/details/gtlmqunrvt.html

struct P { var x: Int }
来源：http://dali.yj20258.top/Article/details/gtjmqugjjf.html

[T26] Swift：类与重写
来源：http://dali.havefunace.top/Article/details/gtywzpiyjt.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gtrapgoemj.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gtngvqkrjl.html

do { try f() } catch { print(error) }
来源：http://dali.yonumen.top/Article/details/gtpbaprbgd.html

[T28] Swift：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtxfcrbibf.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gtuzpoedgc.html


<!-- 参考信息 -->