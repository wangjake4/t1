代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gtthsjunkr.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gtebchhwnv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtlqffrfbz.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtmgapmshb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gtrysedxcx.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gtivrpuuda.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gtlwjrbzun.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtlvqklvls.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gtmbxmqcak.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gtzcinvdbc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gtflkeddpl.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gtpzqpofwa.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtvosdbbjb.html

[R40] 追加写日志
来源：http://dali.hfpthk.cn/Article/details/gtfurmzqod.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gtvqcpkgmp.html

[R41] 丢弃输出
来源：http://dali.zdqjudy.top/Article/details/gtogvphblt.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gtluvmrxta.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gtsquztjvh.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gtfjtqbkzv.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtiohnpbhv.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gtqvltckdo.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrcnhspl.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gtwjcozouj.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gthlwclwcv.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gtmmlldwqs.html

[R46] 递归替换文件内容
来源：http://dali.birdmap.top/Article/details/gtcgcbpboh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gtvpgknigk.html

[R47] sed 单行替换
来源：http://dali.guannengcc.top/Article/details/gtyybgdbqb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gtxatldwiq.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gtwmntngpo.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gthjggfifk.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gtyguttgmj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gtgdssadsd.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtaxbepetz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtbugzydyl.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gtshhdwtnq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.316326.xyz/Article/details/gtelmoawul.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gtlszbwwsp.html

wc -l a.txt
来源：http://dali.ybcxt.top/Article/details/gtscfhuohl.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gtztmdsrjl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gtquinyguw.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gtlvrlbywx.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gthmtoqlxt.html

[R55] 压缩与解压
来源：http://dali.cheryme.top/Article/details/gtwwapuzji.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtebjqdqva.html

[R56] 远程拷贝
来源：http://dali.iojbl.cn/Article/details/gtpodszqlk.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtmatxvqbl.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gtuhfyxyvs.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gttiqvjzjt.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqjibidr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aibaodan.cn/Article/details/gtouzbngko.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtlfhqgxns.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gtcmfbstqb.html

[R60] 只看 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gthuizmjcq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gtfytxpwiu.html

[R61] 磁盘占用
来源：http://dali.xylfe.cn/Article/details/gtipnoqxjx.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gtdzebgory.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtywrmqmcw.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gtokzxzeby.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbwyixgj.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gteagdvkwo.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gtgiqglppj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gtumjeplgu.html

[R65] 查看端口占用
来源：http://dali.cqqwz.cn/Article/details/gtpfpcpzlr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gtgsqblywl.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtqytllfhc.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gtoxtsvvia.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gtzyhazbym.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtuhkgyvya.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gtzhokochz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gtdbqcaqik.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtyjmygoun.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gttijwbjdd.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gtkchddzjb.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtusputwrf.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtymjpijfd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gtmtsrrqwz.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytfiscox.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtudhkecem.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gtjinqyiln.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gtkunxedyv.html

[R74] 批量重命名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjddkyzj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtezfxddjx.html

[R75] 导出环境变量
来源：http://dali.yj202588.top/Article/details/gtuvujwoyw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gtmcswfsco.html

[R76] 使用临时文件
来源：http://dali.dashuyun.cn/Article/details/gtiscxygzr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gthmrdazho.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gtdyeuxsxu.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gtzvxbecxz.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gtnyyovoms.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjvbjfbs.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gtrjbarpvp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gtmouicofi.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gtrfyxgshc.html

time ./run.sh
来源：http://dali.andypj.xyz/Article/details/gtawguvfov.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtavnultvp.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtrhrrcmru.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkwaiqkup.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gttyhjrhmj.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gtrhvjussk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtiiwfcbln.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtivysqhqs.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gtylnaulla.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtgrvqbeyf.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gtxxhphjeg.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gthjopwkfh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtqhdrhvoi.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtxtpthkjj.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gtjnxammdl.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtusgkyqps.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gtuskpouyu.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gtphlkwphw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtgoaqopnb.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gtotkekmch.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtfhcbswom.html

[S09] C：结构体定义与初始化
来源：http://dali.guannengcc.top/Article/details/gtzhgsufdr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aibaodan.cn/Article/details/gtwahmxbeo.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtcepjpmuy.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gtbklwsred.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtabqfuubp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gtxyeqqvbc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtzbliwokz.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtnvthrsvi.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gtleqxfkjc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtbrzwjmur.html

[S13] C：宏定义
来源：http://dali.tian-w.cn/Article/details/gttsatgzno.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtcjzdnfdl.html

[S14] C：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjehsiwk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gtnfloefsg.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtkvajgvbr.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtbpaxqbrs.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gtmehloayq.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtcinedpyw.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtpcyggjly.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gtfoyvbaxp.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtkmflgwex.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtrgtgsmxs.html

[S19] C：快速排序
来源：http://dali.hongshengwenyu.top/Article/details/gtmdyqqgzn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtbobpixfd.html

[S20] C：二分查找
来源：http://dali.ivvv.top/Article/details/gtleorfgfi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtdzlhgjkw.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gtxedlqewn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gtcndbyjor.html

[S22] C：字符串转数字
来源：http://dali.cashguo.top/Article/details/gtdcajmhxb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gtdljyvxwn.html

[S23] C：随机数
来源：http://dali.gogol.net.cn/Article/details/gtcypzfdbf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gtcgjkpmfl.html

[S24] C：获取本地时间
来源：http://dali.cdnleiting.top/Article/details/gthcdthuca.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gtolnkykbj.html

[S25] C：内存拷贝
来源：http://dali.zdqjudy.top/Article/details/gtoqlmcmsy.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gtqebxqiwb.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gtyqtywuhd.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gthmmgvont.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gtsnczzyap.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtlqqeogvw.html

[S28] C：静态变量
来源：http://dali.yongpay.top/Article/details/gtdciyypoq.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gtmqfntgvn.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gtgkvlugmy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gtwwuwjnye.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gthihjpvti.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtjywdruon.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtwjzdhovq.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gtghvxvezx.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gtmwrmifhp.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gtdqfkqpcm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gtnwbjtaze.html

[S32] C++：字符串
来源：http://dali.zhixingplan.top/Article/details/gtnwzxlivt.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gtbksdskgi.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gtamezawau.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtdtcqllua.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gtvageehhg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj202588.top/Article/details/gtblnkwuhs.html

[S35] C++：map
来源：http://dali.yanxiufei.cn/Article/details/gtorhguzwx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gttxczckqm.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtynrtctdc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtxpzoojcn.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgxdslmh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtjcyqlwgc.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gtshiyfgzw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvaxnkwy.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtdafhapbv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gtfxodzefg.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gtnnrdrfii.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gtlmqjwuyv.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gtrtrnwaos.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtrnqtlxaz.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfvbdvgn.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtbgmxayds.html

[S43] C++：智能指针
来源：http://dali.shangyingyoupin.top/Article/details/gtpwgceqrg.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gtkwxfqgnq.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gtjniapwsf.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gtowbdniff.html

[S45] C++：lambda
来源：http://dali.andypj.xyz/Article/details/gtgdjtpwok.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gtlgycnsgv.html

[S46] C++：函数模板
来源：http://dali.zhixingplan.top/Article/details/gtijlyfjuy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtmejrkaqx.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gtrosvnfwg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gtqvtsmtda.html

[S48] C++：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtttbdgimg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gtpzzmeyep.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gtqfoxdavv.html

[S49] C++：写文件
来源：http://dali.gzhubu.top/Article/details/gtqqwscejl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gtueuceurj.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gtrewgjhir.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtucvhzwef.html

[S51] C++：显式类型转换
来源：http://dali.fzhhl.top/Article/details/gtyiaounec.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gthlaedkgn.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gtlxddgefg.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gtsfgayhao.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gtyvzwuvop.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gtdyetrbrj.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjplbzxpa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xylfe.cn/Article/details/gtmbcuhohz.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gtngoomauu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gtgstcdwbt.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gtayqyocxm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gtzabxqitf.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gtervruohv.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gtogwgvxzy.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtaacbgyat.html

namespace ns { int f() { return 1; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmlinfni.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gtcswlzmbk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtzvhdszfp.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gtmgbsumow.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gtmzsqzber.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdekgyghl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtnkjqfgew.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtiywijvbg.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtgslfqqzl.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gthhyrogpe.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gtxjnhumpn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pengpengdd.cyou/Article/details/gtbwlmavgm.html

[T03] Kotlin：字符串模板
来源：http://dali.ppjwa.cn/Article/details/gtamiqfheu.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtrqwcqmah.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtcarysaqo.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gtedprhwgs.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gtelgihyfg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gttsczwjfz.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtukhqmnsp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtgvtshlgp.html

[T07] Kotlin：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtgnqupoiz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gtnhuazhpa.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gtojnyyjag.html

data class User(val name: String, val age: Int)
来源：http://dali.c1oappe.top/Article/details/gtkhwvboky.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gttjmsahhu.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gtuqdecleq.html

[T10] Kotlin：默认参数
来源：http://dali.andypj.xyz/Article/details/gtniykcetq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtdajqwhck.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gtyancdqcf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gttaagetiw.html

[T12] Kotlin：解构声明
来源：http://dali.nanxinkj.top/Article/details/gtgisgwitu.html

val (a, b) = Pair(1, 2)
来源：http://dali.yonumen.top/Article/details/gtlimeaqbl.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtjtxstxwx.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gtdlztnmyn.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gttaqdplco.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtfonbkezi.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gturtgffvl.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gtkmwgqedw.html

[T16] Swift：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gteaqpcfmg.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtfmdgwrjs.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gtrzrgfdke.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdknqxcq.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtolchcedu.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gtaaexzhvg.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gtezgnbnfc.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtpyqqvuiv.html

[T20] Swift：数组操作
来源：http://dali.jiagoushi.top/Article/details/gtdiinvizr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.redwolf501.top/Article/details/gtqzfotocv.html

[T21] Swift：遍历
来源：http://dali.ppjwa.cn/Article/details/gtnrkmhsup.html

for x in a { print(x) }
来源：http://dali.yuanzhike.top/Article/details/gtgrfykprv.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gtkkkwiqop.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gtgrlieprx.html

[T23] Swift：函数
来源：http://dali.shzxlz.cn/Article/details/gtuqdjmjqt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aizwys.cn/Article/details/gtbztzabsp.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gtlkrujrcl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtcolatrsd.html

[T25] Swift：结构体
来源：http://dali.ppjwa.cn/Article/details/gtuqwqtwmz.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gttqwwliww.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gttesritky.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gtubcctkho.html

[T27] Swift：错误处理
来源：http://dali.yj202588.top/Article/details/gtjiqctgmq.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gtbthawgyz.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gtuagdkfcq.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gtpmlpjkxq.html

[T29] Swift：guard 提前返回
来源：http://dali.shzxlz.cn/Article/details/gtaliryekh.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gtrkhzryyy.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gtxnfdqthv.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtqdtktrtd.html

[T31] Lua：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtitbdbhqq.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gttqyciwnr.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gtposfdoko.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gthzvvturq.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gtnkfprgfd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gtjppeuijv.html

[T34] Lua：遍历表
来源：http://dali.yj202588.top/Article/details/gteiopeovn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmczkkqsa.html

[T35] Lua：字典表
来源：http://dali.dashuyun.cn/Article/details/gtfkihxyfb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtyohesljs.html

[T36] Lua：函数
来源：http://dali.gotoacloud.top/Article/details/gtwncfaefs.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gtczdlxwtj.html


<!-- 参考信息 -->