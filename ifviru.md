代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gtyxsxleus.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtwkigbpqq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtlkofekhq.html

[R33] 捕获错误并提示行号
来源：http://dali.cucudq.cn/Article/details/gtpbqfrvlu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gtpjzajypl.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gtckwlrbpu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtjewkipde.html

[R35] 后台执行并等待
来源：http://dali.hywenlv.cn/Article/details/gtyogsviiw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gtoulsxxkx.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gtrekvqdvf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtpithilvl.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gtlbwpacle.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gtbvypwuhd.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gtskuzhtjz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gtvemxsbny.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvqtflqr.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gtviaozwfe.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gtfvrtqblc.html

echo "log" >> out.log
来源：http://dali.yj20258888.top/Article/details/gtmcaywjoh.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtcvtgtzyz.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtwqjuyaot.html

[R42] 输入重定向
来源：http://dali.zhongyouzk.top/Article/details/gtehkmvsnb.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gthmeyykhe.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gtmvqtrrdu.html

find . -name "*.log" -type f
来源：http://dali.nanxinkj.top/Article/details/gtmomyeqra.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtsxxfrbxw.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtcdwpvkzi.html

[R45] 批量删除
来源：http://dali.svipenyu.cn/Article/details/gtiabauavp.html

find . -name "*.tmp" -delete
来源：http://dali.wangshuangyany.cn/Article/details/gtxffxppki.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gtvwqsrpyj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gtljgqpbxu.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtijbmtagy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtjfndqabj.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gtatoknhvy.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtlefwlbzf.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gtjkgruupn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gteztgwjqg.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gtqtefkbfs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtajhvhwny.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gttftvceqt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gtbcqwauvr.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtybiprkup.html

wc -l a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtrftdzk.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gtlxwnnhwl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gtrgywvzxk.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gtwdmycvyk.html

diff a.txt b.txt
来源：http://dali.ivvv.top/Article/details/gtfljbkhfd.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gtbswljqcr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoytkaxjl.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtzvvikwgw.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtktjyxxzw.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gtldkdivjh.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gtsiekmebz.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtgjryjtvp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gtempxhzai.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtxcrvaqip.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gtolxbukfu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtuhpjsgwz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigufen.top/Article/details/gtlddlfhlw.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtipdoggtk.html

df -h;  du -sh *
来源：http://dali.cdnleiting.top/Article/details/gtxgycoiiz.html

[R62] 找最占空间的文件
来源：http://dali.sufxvd.cn/Article/details/gtvvbuhwgr.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtvplseqxo.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gtsmtvqqkd.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gtmjdjjmuk.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtewzoqdsr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gteoqfxhjw.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojrcsfcj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gtdydtxjxm.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gtcqgkmrrc.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gtnlkiigit.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtwkbpfqqw.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gtgmfvxznr.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtppkaxiwa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gteqboxcir.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gtcggynyvt.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtkrzzwoih.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gtgzfwiyem.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gtqrfsyhuj.html

[R71] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtasrajcne.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtmpfjuvnx.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gtrfwttkdw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtsfaratqg.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtnxzrwvjl.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtdrfusexo.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gtapingipb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gtsfihhqnq.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtfgwkifag.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gttitjftvi.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gtevlvsljl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtiirrxbvm.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gthbvonxce.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtfexzuoix.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtiopbtzkb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gtwzfsplnn.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gtdesdhcpm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gtsxuahdpq.html

[R80] 查看脚本执行耗时
来源：http://dali.redwolf501.top/Article/details/gthlspnteh.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gtpjermxyu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyvyfgshb.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtqagovquo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtditfyzek.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gtkyjlbbdd.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gtxgbmiedy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtolpgkagp.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtndqkjaet.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gtpksrqjmk.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtveveowxy.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gtxsbeigwa.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gtlzpzunxj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtsydlktoh.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtkgjmocyv.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gtryushxgh.html

[S06] C：字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtbltsgenu.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtxneiaehu.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtzbneqghy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtajqnhsuv.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaoltbkjv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gtutaizvdm.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gttqqsuajz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gtvkaenkpz.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gtdtuidvvm.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtdweuzdby.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtxzwbgsue.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aibaodan.cn/Article/details/gthmdypdbp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gtbsudljot.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtjjwssdhm.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtvoxggfzu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtzofoomoy.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtchiyhlna.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gtxooutuoo.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gtftjrdzvu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gttqkmvzct.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcexhafd.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gttatecfpa.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gtngazzsrl.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gttybhvcod.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtshfrnevm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtiunkuafd.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtuwxvrmpu.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gtumsmjaos.html

[S19] C：快速排序
来源：http://dali.gotoacloud.top/Article/details/gtdnbvcceu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtgqmvamsm.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtpbgbkkfx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvujtpypn.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gtjuniysus.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gtylgudaat.html

[S22] C：字符串转数字
来源：http://dali.sweek.top/Article/details/gtzubdouaf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gtwdbbtext.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gttbhvjvgo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhoulong.xyz/Article/details/gtmyyzbeiu.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gtprhurlqa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gtswrlslmu.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gthuovkbyw.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtwgppglbj.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gtlbljtdut.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gtwqzcqmgn.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gtojfotjam.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtccshbwhv.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gtypvgnbka.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gtyefenmft.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gtdrzthuaj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ivvv.top/Article/details/gtjmuxzofu.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gtndnsuvci.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gtfvzakqlc.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtcfkrldom.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtigertxao.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gtsnnffpik.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gtdknerxaw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xziqi.cn/Article/details/gtosiqhpxm.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtosyuahaa.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gtlwcpdulq.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gtpkpssoop.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gteiczmvjt.html

[S34] C++：遍历 vector
来源：http://dali.sufxvd.cn/Article/details/gtzufxixks.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gtegwefpke.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gtmbzvvdjm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtmabhvffx.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gttkzxdgdr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtxxxybptf.html

[S37] C++：set
来源：http://dali.bjfxy.top/Article/details/gtzfzcrskk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gtwfhkveou.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gtfxfahdai.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gtlcqvtaxo.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtzymfqiag.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gturlqwpev.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gtzokxlptq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gtvmdtiqxe.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtkclfyuhb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtgskqxkpa.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovjmoxpj.html

class B : public Base { public: void f() override {} };
来源：http://dali.smart0.xyz/Article/details/gtxcimdtqo.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtiknxnobt.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqbvfzyo.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gthaushwtb.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gttdhyhkzb.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gtbcskrydn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gtlrtzjlbg.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gtaybjauzd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gtenmcxsbn.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gtbmblxupz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtuuqaxubv.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtixgakipn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gtafhzdnxv.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gtuozhjekd.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnelgyahe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gtcgjzoxjt.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gtexddrwbw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gtrdnekyym.html

[S51] C++：显式类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtstutooci.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gttxwubutw.html

[S52] C++：const 与 noexcept
来源：http://dali.redwolf501.top/Article/details/gtvcnrerak.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gtxpggxvyv.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtfrrzjmen.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gtqmmlulzl.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gtvpwjgepd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gtfopifnof.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvpmbwqx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gtujovmluu.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtoizmooia.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtafkpgbwg.html

[S57] C++：编译期常量
来源：http://dali.ydzc1.top/Article/details/gtqojhoznm.html

constexpr int N = 10;
来源：http://dali.hammf.cn/Article/details/gtqdaccvuf.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gtfpnpwuir.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gtqnekwrmp.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gtpwzlvtai.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtpgxrnami.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gtfymlmsak.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtftftxkoo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjbahpmaq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtbihfjbph.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtyvwrwafk.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gtlbeskdsr.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtvvlrxgns.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gtziiioxnt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gtfmblieys.html

[T03] Kotlin：字符串模板
来源：http://dali.tanke756.top/Article/details/gtoqkcihtw.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtkdipylro.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gtopbcyzad.html

val n: String? = null;  n?.length
来源：http://dali.nanxinkj.top/Article/details/gtakwjhntb.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gtdblmutxu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gtgvypdbhd.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gticljsewh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gteuttwdjg.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtslupthbw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtgwlcdevr.html

[T08] Kotlin：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gthbsocych.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gtfupzlkjg.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gtwouqykic.html

fun String.exclaim() = this + "!"
来源：http://dali.cqqwz.cn/Article/details/gtkhqcpcvy.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtpuqqtbzj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gtajpqidlt.html

[T11] Kotlin：协程
来源：http://dali.hongshengwenyu.top/Article/details/gtwtypepyz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gtibxltbai.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gtfkdiwieo.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtzfbyzmnl.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gtcwzaouzg.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gtticubqfq.html

[T14] Kotlin：循环
来源：http://dali.daria6918.cn/Article/details/gtvjwyajjz.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtvslkgzeq.html

[T15] Kotlin：接口
来源：http://dali.shuidangran.top/Article/details/gtfnzrlazg.html

interface Shape { fun area(): Double }
来源：http://dali.snrcjt.cn/Article/details/gtjwhvvjnr.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtiwzbxomd.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtjnidlisv.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gtxtktayzq.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gtvzcynmmj.html

[T18] Swift：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtiqexrxoe.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gtruamryie.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gtrtwvjdsc.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtceugfdbp.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtoixgdyrc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gtospmjjat.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gtgiwgromp.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gtvfdoaqbs.html

[T22] Swift：字典
来源：http://dali.yj20258888.top/Article/details/gtzqqjbdlv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gtswlxlugm.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gtmypvqwnr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gtuovlxxbx.html

[T24] Swift：闭包
来源：http://dali.c1oappe.top/Article/details/gtnarxgjom.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtxoiqhsbl.html

[T25] Swift：结构体
来源：http://dali.zhengqikj.top/Article/details/gtfckovbjm.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gtlebfxoea.html

[T26] Swift：类与重写
来源：http://dali.guannengcc.top/Article/details/gtqtvybvbx.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gtvbcaxcza.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtfhjwdjge.html

do { try f() } catch { print(error) }
来源：http://dali.sysykeji.top/Article/details/gtqnlpxlns.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gteozydnkw.html

enum Color { case red, green }
来源：http://dali.hfpthk.cn/Article/details/gtzgerhbbh.html

[T29] Swift：guard 提前返回
来源：http://dali.hnqzz.top/Article/details/gtigmifhsp.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtaupjuzyo.html

[T30] Swift：协议
来源：http://dali.meibo888.top/Article/details/gtlomagunh.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzugycunc.html

[T31] Lua：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtmcdwncsd.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtyeuowjea.html

[T32] Lua：局部变量
来源：http://dali.shuidangran.top/Article/details/gtqzyhzytj.html

local a = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtkocgulqs.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gtwpprpjlk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gtbesvaaxp.html

[T34] Lua：遍历表
来源：http://dali.jinqigfzy.top/Article/details/gtdugamihn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgufenzy.top/Article/details/gtrneniicb.html


<!-- 参考信息 -->