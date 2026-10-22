代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtaodrtnuq.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gttxwyeduj.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtyexduday.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gtginguxfi.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gtrhmkxney.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gtiqcyufhx.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtcoxygemm.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtxuekwtee.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gthlahxqtl.html

[R30] 函数返回状态码
来源：http://dali.sxryk.cn/Article/details/gtickjbncq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtrzncfsyx.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtfkmnwnfx.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gtdndnggrb.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtuuddwyid.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtymeranrk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gtoxltplxe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pycfn.com/Article/details/gtgxewjgay.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gtlimmbyun.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtgfcsixhh.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxeigjgy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gtrfnowglr.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gtxzhqzewv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtnqxajauv.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gtunbrulhk.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtxerpdokm.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gtfgjzjkdg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtxzeorgxg.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gtknidcpds.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtuweknzvj.html

[R40] 追加写日志
来源：http://dali.wangdashe.top/Article/details/gthajuzznu.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gthesfdedt.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gtsgbjwrof.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtkghddatz.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gtitycrewe.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtwdlepkho.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtdxkvosqj.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gtpwtemfca.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtzrzudixf.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gtqvmfwfrp.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gtmlqanwci.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gtaamixusu.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gthukxduxw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gtsdhweahf.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gtrxgzviws.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtzjmknyvj.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtmyiufbny.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtasmrasmf.html

[R49] awk 带条件
来源：http://dali.zhixingplan.top/Article/details/gtrvobncin.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtpeewgauf.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gtculwrvdf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gteabnjhdj.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnnyhjon.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gtqxejyyko.html

[R52] 统计行数
来源：http://dali.daxiang520.top/Article/details/gtywvvcyph.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gtyhpnqpkn.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gtjyfklhke.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gtptgozdig.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gticxfivwd.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gtmhlogwti.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gtfzzafodz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gtxctowkfg.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gtvcvjuxtt.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gthejvygfz.html

[R57] 远程执行命令
来源：http://dali.hfpthk.cn/Article/details/gtritflhvb.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gtlcykmaru.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gtghxpnlcr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gtrotvrkpb.html

[R59] 发 POST JSON
来源：http://dali.fengsongda.top/Article/details/gtszxkqhad.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gtshpiwxrq.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtmxsjuejq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gtuebwzycm.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gtvynhxgyw.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gtcqudheww.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gtxycwgkuj.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gtxyhhpftu.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gtldxjvoic.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gtgbqjanve.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gtrchpdbax.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtgkbgdhlm.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gtgubkkzga.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.iojbl.cn/Article/details/gtbuflusyk.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gttooachfv.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gttcswflol.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtixvvnfxr.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gtthuzbobm.html

[R68] 计算文件校验值
来源：http://dali.andypj.xyz/Article/details/gtmqittkof.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gtphecksnt.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gtydfxjyuq.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gtqeeiwwkz.html

[R70] 时间戳与互转
来源：http://dali.sxryk.cn/Article/details/gtbkajmzxr.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gtdwnuguge.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtnlhqhnzw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.birdmap.top/Article/details/gtxxaxmmmf.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gtcqglkofs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtzayjadwd.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhtivdpm.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gtqfzktldj.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gtbljoywpn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gtiipcpmpu.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gtxiftexjm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gtyzacoess.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtqesuzjgj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtcssrohgt.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gteshdqzvs.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gtkbuuilzj.html

[R78] 交互式菜单
来源：http://dali.havefunace.top/Article/details/gtpovtkiqj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gtafnobyfp.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gtfmgthelq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gtzjpnfvka.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gtlerrlbzt.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtsuoiarsm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmbrzliwx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtqziixkur.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtyzuozgcr.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtoffruqsv.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gtpmmpsdih.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gtcrjuqkpz.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtaiacrafj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gtyluwgkbv.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gtpdobqobq.html

int x; scanf("%d", &x);
来源：http://dali.cucudq.cn/Article/details/gtcshkggzb.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtastustcx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gthdkytqdz.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqooueqc.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gtbkhkaynk.html

[S06] C：字符串比较
来源：http://dali.pycfn.com/Article/details/gtobzsweow.html

strcmp(a, b) == 0
来源：http://dali.daxiang520.top/Article/details/gtpkhgmqhb.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoalagln.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtaucsbneh.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gtvtcshbve.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gtnuzztwph.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gtjkqnszgm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gtvclnmtmp.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gtkgroqffm.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtkxcbzufi.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtzelmawsj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gteurpjjqe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gtszmzlvno.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtkepumkrh.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtxoghlkqq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtohzstkub.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gtengbzkry.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gtqbkqjczl.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtfmsgcinw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.c1oappe.top/Article/details/gthbqqqqxl.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gtqsgdiiyb.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gtneipaglb.html

[S16] C：位操作置位
来源：http://dali.chenlongwang.top/Article/details/gtujjnpcpq.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gtnrzgglzf.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gthwifuctu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gtckevvtrq.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtilxattyf.html

int main(int argc, char **argv)
来源：http://dali.jqgfzy.top/Article/details/gtqwapwull.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrkdrtkj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtwmosplpx.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gtovpncpsf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtmednvudb.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gtbcwnrxir.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gtudihtphg.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtdmdfubzp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gtwkwccbqr.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtrrnegiix.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtrxtbwmdi.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtkytglzlc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gtziudstmh.html

[S25] C：内存拷贝
来源：http://dali.gzhubu.top/Article/details/gtjczdkdhz.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gtxabvhskv.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gtwxlsmsfr.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtrxbtliva.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gtgsuigkkb.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtwfsvlhwl.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtrrjyfpho.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gtxniykbqk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gtsbtoqzdf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtxzvqewga.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gtyjghaume.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtklnstlfk.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gtlymbcfmo.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gthrpdgsnd.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpvrufam.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gthxlaqski.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gthvlzkhix.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gtwdrqdvin.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gtkhvtaepy.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gtqcgzazzd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gtrmrzidee.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gtpakdvwge.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gtynzmfhby.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gtpphixeza.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtoahpztfk.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gtbkoqutme.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gthrszzkls.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gtfacpmevt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gtdbxwtxyd.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gttcargrpt.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtofjhgqub.html

[S39] C++：自定义比较器排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpftxnlk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gtbjajbkdo.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gtcgmsrmmu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtzupzjsar.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtnndtqnhi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gtoyazknbc.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gtkhzvmfgs.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gtbcqiarnr.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtlanjpbgj.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtfkixkffp.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gtslqromjn.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gtsbfsbkca.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gtzoaacurv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.0kj1m.cn/Article/details/gtxjahsnng.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gtjayhqdsp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gtdulrkssg.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gtmpnxknkj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gttgtjupfo.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrehikov.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikvsqukr.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gtbaajppsg.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtumpkloqu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gtybnlkymi.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gtwynjswqi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtoswufrxu.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gtqoussrht.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtcfllcnqx.html

[S52] C++：const 与 noexcept
来源：http://dali.chenzaomai.com/Article/details/gthgphefmt.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gthfgewtyo.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gtfykdhwnz.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gtbtezysgx.html

[S54] C++：异常处理
来源：http://dali.andypj.xyz/Article/details/gtetkftukv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtqyvuxohp.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gthjcpbhfe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gttnwcprqc.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtlzztiann.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gttlunsnbf.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtjqxdleiv.html

constexpr int N = 10;
来源：http://dali.sxryk.cn/Article/details/gtgoywffwm.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gtojionvbg.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtllgxwhsu.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtrokfjtqg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtssoriavo.html

[S60] C++：遍历并删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtaoommvrk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtqripfgfb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttmeevleq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtiiuhnmbm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtpebgyytn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtuollghcf.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtxldzuqqd.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtrazktloi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gtlekqlbeq.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gtrglqmdtq.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gtilqxctum.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtksamjvpv.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gthpwpozds.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gtcmmtluzb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gtmxbecsjn.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gtumczvlvd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtivvdwygk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtextwqehg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanikvmin.html

[T08] Kotlin：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtmxnwwygr.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtipddrnxk.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gtvotxedti.html

fun String.exclaim() = this + "!"
来源：http://dali.pengpengdd.cyou/Article/details/gtxuptnlqh.html

[T10] Kotlin：默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtgcviktye.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtbreofyqh.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gtydppjokn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gtlpxabhyv.html

[T12] Kotlin：解构声明
来源：http://dali.yueranfly.top/Article/details/gtxyqobdin.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtqyznmhjk.html

[T13] Kotlin：只读 Map
来源：http://dali.shuidangran.top/Article/details/gtxhunsuyn.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtzdmeppof.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gtceuecjnv.html

for (i in 1..10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gtdsagngwi.html

[T15] Kotlin：接口
来源：http://dali.chenjidiqi.icu/Article/details/gtrdkikznc.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gtkgrmkrzo.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtmqyvbjbo.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtstrwqphh.html

[T17] Swift：变量与常量
来源：http://dali.yueranfly.top/Article/details/gtyxnllspn.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtdpawvjkf.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtbfflrkst.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gtzqmxvrbl.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gtblhykcid.html

if let n = opt { print(n) }
来源：http://dali.cheryme.top/Article/details/gtppgyidph.html

[T20] Swift：数组操作
来源：http://dali.cdnleiting.top/Article/details/gtrclbjovd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gtqopcevjv.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gtcjokeimb.html

for x in a { print(x) }
来源：http://dali.hongshengwenyu.top/Article/details/gtdroahgnl.html

[T22] Swift：字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdspgamx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gtrwcbyhyh.html

[T23] Swift：函数
来源：http://dali.xylfe.cn/Article/details/gtarozqiyt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gtwibtcytk.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjdrjzpc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabbhyqwb.html

[T25] Swift：结构体
来源：http://dali.yongpay.top/Article/details/gtkvispajk.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gtfxzxewlk.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gtzrxspysw.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gtghllwqei.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gttxklkkit.html

do { try f() } catch { print(error) }
来源：http://dali.sysykeji.top/Article/details/gtnkzoucvn.html

[T28] Swift：枚举
来源：http://dali.redwolf501.top/Article/details/gtmxtfzsgx.html

enum Color { case red, green }
来源：http://dali.zhixingplan.top/Article/details/gtqduohjfv.html


<!-- 参考信息 -->