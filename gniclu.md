代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gt2uejpqpcy.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gt2rbhnhnyw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sysykeji.top/Article/details/gt2cvfeboqo.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gt2kxjybhpf.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gt2mfyczgco.html

[R38] 管道串联
来源：http://dali.gogol.net.cn/Article/details/gt2rbtgfuru.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxyiywm.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gt2eioccvkk.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2tymytygc.html

[R40] 追加写日志
来源：http://dali.sufxvd.cn/Article/details/gt2gjrhllkw.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gt2lgtiretx.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gt2ldwoznai.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gt2wqtpoogy.html

[R42] 输入重定向
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgbhnkjl.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gt2vgcxqkze.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gt2fhfiimju.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gt2uuoakwui.html

[R44] 按修改时间查找
来源：http://dali.zhiwuduotai.top/Article/details/gt2ossbtgyp.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gt2akkbzufs.html

[R45] 批量删除
来源：http://dali.xuanzx.com/Article/details/gt2qppcemqv.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdvzcjqt.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gt2zrzhprro.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gt2yexvaqpo.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gt2fncnxkur.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2hueynjfe.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gt2tsjnpktj.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhfksolz.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gt2zfyjncca.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gt2efxrxoie.html

[R50] awk 求和
来源：http://dali.ehwqpu.com/Article/details/gt2ifslgwbx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2fzvqvnmb.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gt2lwflevcz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gt2vrljxqit.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gt2wuuotmyj.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mupofscm.html

[R53] 查看文件头与实时尾
来源：http://dali.svipenyu.cn/Article/details/gt2wceoovto.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gt2okgloapa.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gt2subajeet.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gt2qeuzqsql.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gt2yhsdjngg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gt2udqbxfyd.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gt2xoeujyjm.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gt2iukqiwom.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gt2mixbkhif.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gt2hpcpwvpz.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gt2gwfchyov.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gt2zgultjdb.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gt2wvekqves.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gt2gdxfmdvw.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iskkqnqx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrmefmpc.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gt2opytcpvv.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gt2hhgqjqld.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gt2mdpsgxzn.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gt2vytxinee.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gt2puloxjls.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyowdkzk.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gt2cuyzoqis.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gt2spjbuihc.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gt2kaweuqnv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gt2smaiwomj.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gt2pcjmdrke.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gt2kixutrxa.html

[R67] 生成随机十六进制串
来源：http://dali.yj202588.top/Article/details/gt2fkmtgoyp.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzhnubeh.html

[R68] 计算文件校验值
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlvrqdha.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gt2qjonqeze.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gt2gpkyaqvh.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gt2ilelrsjd.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gt2xjialhpn.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfilixww.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gt2qtgajqji.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gt2acffyema.html

[R72] 等待端口就绪
来源：http://dali.zhixingplan.top/Article/details/gt2towrieno.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2wnxuoqfc.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gt2emuyzvav.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gt2xegwmdas.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gt2kelnvtqy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gt2mzbwbnff.html

[R75] 导出环境变量
来源：http://dali.cqqwz.cn/Article/details/gt2nrtfpmbo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hammf.cn/Article/details/gt2ysbwolpw.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gt2rpqnybmh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gt2pwjonrwc.html

[R77] 读取用户输入
来源：http://dali.jqgufenzy.top/Article/details/gt2gcxsewel.html

read -rp "请输入: " ans
来源：http://dali.yuanzhike.top/Article/details/gt2dnotunkw.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xeyyhwfv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gt2lbwznezi.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gt2woxwsgoo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gt2aydnoygh.html

[R80] 查看脚本执行耗时
来源：http://dali.fzhhl.top/Article/details/gt2nmottcsx.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gt2pfmjzxvx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ozjuilzo.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfayzknp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ctzqknys.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2iwhxsamk.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gt2yuqsnyfn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gt2nludryjf.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gt2enysmqbf.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gt2sqrfppxa.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gt2ycilqvrk.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gt2hzkkgavk.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gt2qznewere.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuxming.cn/Article/details/gt2hrjmnhuq.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gt2myskyxdp.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gt2qbghjxku.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gt2lcvyfbpr.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gt2xudikkuh.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fljaxbja.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gt2suhtoxuf.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrlazgng.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258888.top/Article/details/gt2ncgwlvyb.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gt2gajulbnw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gt2whkxvwzl.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gt2dfdgzczk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2doxamnvl.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2rxsqqult.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gt2ryqetfdk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gt2oenjoaof.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gt2brxkmpyp.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gt2xlkuocfi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gt2kbhcmylj.html

[S13] C：宏定义
来源：http://dali.zycfv.cn/Article/details/gt2zovvcygs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gt2kmiivirx.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gt2rxpmpfts.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigufen.top/Article/details/gt2kgafxavv.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gt2aqrawyqk.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gt2oiyihdhj.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gt2gnahyhra.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gt2ehqkaekp.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2rontayud.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mduxjdeh.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gt2dpfsaxxe.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmlnynqo.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gt2dmhhtzdk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2evxecamm.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gt2vfxiqbrg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2dtxkxkms.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2sewjpkyc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gt2xoprfrsd.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gt2owawznib.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gt2elbulhmm.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gt2xqaqyhkt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gt2sywspixk.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gt2mavaefwr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnmsmmno.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orqaaqbf.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gt2zvlnerwg.html

[S26] C：内存清零
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqufcfes.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwlewuwz.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkqtkbbn.html

const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2kbebchkg.html

[S28] C：静态变量
来源：http://dali.snrcjt.cn/Article/details/gt2tmoddpol.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmgwcmfk.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gt2unxtikmw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gt2mmdyenah.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gt2grqlfnli.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gt2pympqgyr.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibkvjbhv.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gt2orsungkj.html

[S31] C++：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2xgwiyyvp.html

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gt2zdrubwnu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmiktjvk.html

[S32] C++：字符串
来源：http://dali.gogol.net.cn/Article/details/gt2jdbvhpuc.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gt2ocettslt.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gt2uwuvzwmq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxinkj.top/Article/details/gt2ohfbkxtp.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gt2breuscae.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gt2flcbclly.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gt2lmanicqr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2shvgktnv.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gt2huaveeyt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2aqnoppvq.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gt2lllspwag.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gt2rgyrsjce.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gt2nfvvldmh.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gt2qcflnmgs.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jejrfxdm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gt2knmlatxt.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gt2gnykaxxv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2fbpwneeb.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2wqewazas.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gt2whperebk.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gt2nacnoidd.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gt2xsdqxhqr.html

[S43] C++：智能指针
来源：http://dali.wangdashe.top/Article/details/gt2albziypy.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gt2shlckuos.html

[S44] C++：引用传参
来源：http://dali.daxiang520.top/Article/details/gt2pmhvlhbs.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2idmtqhpg.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gt2eqoenmbv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gt2kyxuqsgi.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gt2uayvxuxt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2krvnjkjh.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gt2ihksjoij.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gt2fffnupmi.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2onvsxncm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gt2knmkrgbd.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gt2poszlvlx.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gt2wvtwborp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gt2psscteyy.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gt2lgdezdzf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2uhkenydx.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gt2vjasgalb.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gt2ihgmbczi.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gt2htbirrar.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gt2avxgysey.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gt2wfhwmnjt.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gt2pchwieba.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gt2yhmlaqdu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2squincdi.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gt2zdjjswgi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hammf.cn/Article/details/gt2fiyvhoxm.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gt2kvjquhjq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangdashe.top/Article/details/gt2qyrdkmif.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gt2fovmggun.html

constexpr int N = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2svntlzbg.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gt2rbygcmdd.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2kzxagmmr.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gt2cykxtmgp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pequuiku.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gt2qezepmkn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gt2yvvzotww.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2milaoyxz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gt2rlqrmxxo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2mufyxsku.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2fuouyqzq.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2dstmvqyg.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gt2suqelcjb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gt2iazqcyur.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gt2fcjigrat.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gt2bhbowyqj.html

[T04] Kotlin：空安全
来源：http://dali.wangdashe.top/Article/details/gt2rfmhlleu.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gt2bgrvlpvp.html

[T05] Kotlin：when 表达式
来源：http://dali.guannengcc.top/Article/details/gt2vtnwfbam.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojukwrsp.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gt2xndxnhnu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2puzcdefv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2entwlgba.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gt2wwhobnmc.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gt2kgjevnrs.html

data class User(val name: String, val age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyxlukhe.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gt2mjdrmqpl.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gt2xcgnuxpq.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gt2zqmsqzjo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gt2qritpbhi.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gt2mpzkparr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfzwxwj.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gt2xwfxosjf.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2awlpvzex.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gt2qnmazipt.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gt2thvwpkql.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynoxjqbc.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gt2njmdyqja.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gt2irawlrpv.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gt2xlkrhfzw.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2ngurqkhd.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kyucjynx.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gt2ahkfnqpd.html

var a = 1;  let b = 2
来源：http://dali.wangdashe.top/Article/details/gt2mbkgzcdy.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uvjervkp.html

"值: \(b)"
来源：http://dali.c1oappe.top/Article/details/gt2lgaguapr.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gt2vjrtgcmw.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gt2izcfxmyf.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gt2vwybjlav.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2kowzteay.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gt2asgaowhr.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gt2agocvkeu.html

[T22] Swift：字典
来源：http://dali.yuxming.cn/Article/details/gt2ywcmuqbx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gt2vrhpmikh.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvgoxorv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gt2dxakeeyr.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gt2mszvgwtd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2ipcwkpmf.html

[T25] Swift：结构体
来源：http://dali.tian-w.cn/Article/details/gt2vfqlbfef.html

struct P { var x: Int }
来源：http://dali.cdnleiting.top/Article/details/gt2iexayxpa.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gt2jsomknmk.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csiwcksy.html

[T27] Swift：错误处理
来源：http://dali.sxryk.cn/Article/details/gt2xgubpbkc.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gt2hvflmdrw.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2rcqbyikc.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gt2youetaqx.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gt2yvhijodf.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gt2icxbbhws.html

[T30] Swift：协议
来源：http://dali.jyoumei.cn/Article/details/gt2tocjzotv.html

protocol Shape { func area() -> Double }
来源：http://dali.xuanzx.com/Article/details/gt2fizytmmz.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2ocwyzywx.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pfcskzxd.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gt2zxmtuskt.html

local a = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2pykcgicj.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gt2bpmgqzjw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ivvv.top/Article/details/gt2xwskdirv.html

[T34] Lua：遍历表
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvvapxlm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.mhx1999.top/Article/details/gt2tufiotli.html

[T35] Lua：字典表
来源：http://dali.havefunace.top/Article/details/gt2cvcaqnsa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hammf.cn/Article/details/gt2difqlnld.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gt2lxbkzphx.html

function add(a, b) return a + b end
来源：http://dali.hnxiangtu.top/Article/details/gt2quikotcm.html

[T37] Lua：字符串拼接
来源：http://dali.nwbrower.top/Article/details/gt2nuusluzl.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gt2tnwyzqkz.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gt2hlbuhpfa.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gt2msmgfbah.html


<!-- 参考信息 -->