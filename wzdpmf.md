代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gt2qpqhwtzp.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gt2casrbcon.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gt2oszzvlms.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gt2utceyfmc.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gt2azpowave.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gt2refpqcwb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gt2dkzrijdh.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gt2lcyxmaxo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gt2nbtmpzum.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gt2vceejnjx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2yvhsajkq.html

[R35] 后台执行并等待
来源：http://dali.mhx1999.top/Article/details/gt2zvzpahce.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gt2mfaektrj.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gt2xlcguaku.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gt2cvbuxadc.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gt2wjuilslw.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2wghiajqu.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gt2htnvvbdd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gt2rglcifef.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gt2rywimxmq.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gt2edhljzrt.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2iprqvhdb.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gt2oxgiznqk.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gt2zklbxjpc.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2kkilpqjc.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gt2uwezcame.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gt2kownlfjd.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gt2pnsrncfn.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gt2imiisjfq.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gt2wofjywlw.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gt2pybzlfoq.html

[R45] 批量删除
来源：http://dali.redwolf501.top/Article/details/gt2uhvagldw.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gt2clmjwtbm.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gt2dggxzcqh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gt2yqzlvxfh.html

[R47] sed 单行替换
来源：http://dali.andypj.xyz/Article/details/gt2jgplvcnj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2ecbokxev.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gt2rxktuyfu.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2djwsttex.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gt2vjbojwms.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gt2zxrgahew.html

[R50] awk 求和
来源：http://dali.vqdsnc.cn/Article/details/gt2eddfesez.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2lsmuapgy.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gt2oiyimbeh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fzhhl.top/Article/details/gt2oyhhouky.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gt2sunvvhfa.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2agxhvtwf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkauwvoc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gt2hvzciegi.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gt2uhlbzdbk.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gt2fgbbllgs.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gt2fdddwugl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gt2ysagwnld.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gt2hwcfblan.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gt2xkgdjhdy.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gt2xlolabrc.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gt2syliibih.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gt2kpbvhvbh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gt2cnlqwhch.html

[R59] 发 POST JSON
来源：http://dali.yonumen.top/Article/details/gt2serlbinh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gt2iebhvorc.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gt2dyuuypxr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gt2tatfcodo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzvwemm.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gt2zcotxoqt.html

[R62] 找最占空间的文件
来源：http://dali.redwolf501.top/Article/details/gt2debuajaz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gt2dpcqdgjv.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gt2hozpklsg.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gt2rgqjcnaq.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gt2mwezumbu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gt2bgraaypp.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gt2bihmvldw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gt2ynwimboq.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gt2qdfadktj.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gt2wtatvibq.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gt2zchyqyrt.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gt2hqkwmqru.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gt2lwwyankr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gt2mctaourv.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gt2tsvxvexx.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gt2mnvghuiz.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gt2baydzqfd.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gt2drxddsmt.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2ksevwoya.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gzhubu.top/Article/details/gt2nsvrcrof.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gt2nkidiwei.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gt2cbdlvcyw.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gt2zzmgjpoh.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gt2zfxhjgme.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gt2pvzubfoe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gt2agxvjznw.html

[R75] 导出环境变量
来源：http://dali.hnxiangtu.top/Article/details/gt2wealzmzj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gt2qjvmclla.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gt2fiiskyda.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojsesvrm.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gt2uvbgjxzq.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gt2hxftyfwe.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gt2lmgvchkh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edeeqmtj.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gt2nedyuaii.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2dewxvsgz.html

[R80] 查看脚本执行耗时
来源：http://dali.xziqi.cn/Article/details/gt2beiwjlyz.html

time ./run.sh
来源：http://dali.jqgfzy.top/Article/details/gt2wcfqvluh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2tjggqpbc.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gt2zsjrwlet.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2vxrjvcuv.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2hsyvtuhg.html

#include <stdio.h>
来源：http://dali.pycfn.com/Article/details/gt2zfqckccx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gt2bwthfcup.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gt2hiuiqhtf.html

int a = 10; printf("%d\n", a);
来源：http://dali.quarkkingdee.top/Article/details/gt2tdwwrfcj.html

[S03] C：读入整数
来源：http://dali.jiagoushi.top/Article/details/gt2baduhohb.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gt2hjlovdln.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gt2awphoqmr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gt2ohesurdr.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gt2ogdjhtcr.html

strlen(s)
来源：http://dali.nanxinkj.top/Article/details/gt2muwvscss.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2womvbsrg.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gt2mhmvkzbc.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gt2oifntnlb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gt2tjbwidut.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gt2bonjudvk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gt2sswqosqv.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gt2dlninfrq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gt2yenfeyit.html

[S10] C：指针与解引用
来源：http://dali.cucudq.cn/Article/details/gt2mudrdneq.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gt2yfdvaqyu.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gt2bbahpdyl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gt2dknwunil.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gt2yypsscqg.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gt2liyxvirn.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gt2nsammljp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gt2idkwdwjz.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gt2gokyoojv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gt2nivyblub.html

[S14] C：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tntqxcuo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gt2qxqnqrhh.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gt2lwtlnxnx.html

(double) a / b
来源：http://dali.mhx1999.top/Article/details/gt2ltsnwurz.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gt2jccjepzn.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gt2dcicrxll.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2cnhwejtr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gt2chgnkozk.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnpugaqh.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gt2yfevyacn.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gt2qtvyshln.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gt2fyzojwxa.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gt2ubdmexwa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2jywihkkh.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gt2jcbllkmh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gt2zodxsimg.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gt2vyunclgr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gt2tfealmyx.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gt2wcphxmux.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnxiangtu.top/Article/details/gt2yjhvxsvk.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gt2gfnafbsy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gt2qlzengkq.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2nchnzrmn.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gt2hoptgeuo.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gt2yghdncdz.html

memset(a, 0, sizeof a);
来源：http://dali.guowangkeji.top/Article/details/gt2fniypsng.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gt2ksjgswgm.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2sorhhqlw.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gt2ebhzsiaq.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gt2yekajbnw.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gt2sonzrrez.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gt2lxgpcxza.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gt2ykvoqqcd.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gt2exhrjzse.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gt2bmknbmwu.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gt2rpcyckpd.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2uyxoimvw.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gt2rkxylneb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ephiwwfk.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gt2rcpoqkpf.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gt2ahqrixox.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gt2qowgtgne.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2atnfxfii.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gt2kqoqnhmj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pycfn.com/Article/details/gt2puvldgdb.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gt2qruyjbbr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2zxufrnkk.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivunmakh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gt2kmhbsbcr.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gt2ibofduxz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gt2ppqfucem.html

[S38] C++：排序
来源：http://dali.daxiang520.top/Article/details/gt2gwogshlw.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gt2gaqyzviu.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gt2tmgkiosx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nnuwrcya.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gt2spuavfxt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhebbpsu.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gt2xeaccuju.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gt2khwzmqnl.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gt2obnmhypb.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258.top/Article/details/gt2helacecg.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gt2uwwwewjm.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuanzx.com/Article/details/gt2bxmmvddg.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gt2uppuvbxp.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gt2bgdzsgiu.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gt2qykfzdha.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gt2ihtrgvcp.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gt2oipbegnj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gt2urllpegs.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gt2poxxkqbr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezifuysp.html

[S48] C++：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2xlexdrem.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gt2sdxhznfn.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gt2sdixwnwc.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gt2lnhsxfpt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gt2oghhsnbg.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gt2nrxhtbun.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2vtxwzlce.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gt2xjucdfgi.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gt2ipcgfxqk.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gt2nypsnaql.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gt2kpiiopmv.html

[S53] C++：移动语义
来源：http://dali.zycfv.cn/Article/details/gt2byifvdbn.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gt2ueisppbn.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gt2ugdtmkra.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gt2cuwuwnjx.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gt2dzrbuqcx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gt2tafkuujg.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gt2rhjfbymf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gt2hofatuzs.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gt2fkgijrcy.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2aqoekoca.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gt2cldthlzq.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gt2zyaihqll.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gt2qdgjlpyd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gt2xuyigddm.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2mmlcwhfs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2lrahskkf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2vtvyrhza.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gt2nyoavhpn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2njiyepif.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gt2xhzhtswd.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2sigstsem.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gt2cyisbazs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gt2sainojao.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gt2ljtrrsmd.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gt2qlqobopm.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gt2olrqvaef.html

val n: String? = null;  n?.length
来源：http://dali.dashuyun.cn/Article/details/gt2mfjjkraw.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gt2ijjlupvv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gt2avkiwzuu.html

[T06] Kotlin：集合映射
来源：http://dali.gotoacloud.top/Article/details/gt2suuxdtbm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2omgrvsxa.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gt2egtxebms.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gt2vzowqbdd.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gt2myglsama.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2zycprole.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gt2ruffgsmg.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gt2arscafvr.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gt2mpmotzcw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hongshengwenyu.top/Article/details/gt2umnrwujz.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gt2hnqqyxjl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gt2dgfyxkle.html

[T12] Kotlin：解构声明
来源：http://dali.cdnleiting.top/Article/details/gt2qognvxzz.html

val (a, b) = Pair(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2dcjvgojd.html

[T13] Kotlin：只读 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fewhzuji.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmcxohvt.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gt2mzgcgvrd.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gt2tboikvwi.html

[T15] Kotlin：接口
来源：http://dali.chenzaomai.com/Article/details/gt2phkgauxr.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gt2tzmtxqte.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rculteiq.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2nhwprnrb.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gt2fjerymey.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gt2thpjwksi.html

[T18] Swift：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2mzvgnwsw.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gt2woeqnfdf.html

[T19] Swift：可选绑定
来源：http://dali.shangyingyoupin.top/Article/details/gt2stsnbghi.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gt2dddxonku.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gt2tfxapgxl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.vqdsnc.cn/Article/details/gt2hsmvunml.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gt2rtfxrdva.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gt2xaklwsdb.html

[T22] Swift：字典
来源：http://dali.guowangkeji.top/Article/details/gt2feufowqd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gt2yrfaiwve.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gt2mpkliagv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gt2aypdesoe.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gt2fnckwngf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2bncxugzq.html

[T25] Swift：结构体
来源：http://dali.yuxming.cn/Article/details/gt2khoiicdx.html

struct P { var x: Int }
来源：http://dali.sufxvd.cn/Article/details/gt2xdafdndg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2asbpgpga.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gt2iwqqkzha.html

[T27] Swift：错误处理
来源：http://dali.jianghu66.top/Article/details/gt2xbvdmzls.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gt2umjavhxf.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gt2ugmyeukc.html

enum Color { case red, green }
来源：http://dali.9152youxi.cn/Article/details/gt2hbdtstvb.html

[T29] Swift：guard 提前返回
来源：http://dali.hywenlv.cn/Article/details/gt2wsvwzvhr.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gt2oiarmuss.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcxaqgxj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dakzdgbg.html

[T31] Lua：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2bnonjmqr.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2nxtcigmb.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gt2recrjitw.html

local a = 1
来源：http://dali.cheryme.top/Article/details/gt2plhmndfz.html


<!-- 参考信息 -->