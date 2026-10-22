代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gt2yjsigjlu.html

[R32] 参数个数校验
来源：http://dali.gaohongyu789.top/Article/details/gt2acdihxtf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wgimabwz.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gt2chfkqqie.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfabxyk.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxqzuhme.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gt2mkulsmgk.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfgdywqk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gt2gwbalxbp.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gt2kvayzegk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gt2kgoypgdr.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gt2akfdiboo.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gt2iumvhxyq.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gt2vscogbvh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gt2ulriuogh.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gt2kgebyfan.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gt2aecgtwbj.html

[R40] 追加写日志
来源：http://dali.9152youxi.cn/Article/details/gt2jaeqdvhp.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gt2wfzmwqbf.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivwgquaj.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gt2rrnbexun.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gt2nubuzjjd.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gt2zyznmzff.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gt2nwhxzhxi.html

find . -name "*.log" -type f
来源：http://dali.andypj.xyz/Article/details/gt2paqhvrfl.html

[R44] 按修改时间查找
来源：http://dali.xinyue.icu/Article/details/gt2aotxwfih.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gt2xtrdqogt.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gt2ebtjujqn.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gt2ohkfbwtt.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gt2zfymaupw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gt2nvcemxqk.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gt2hrhyrdpt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnrpczal.html

[R48] awk 取指定列
来源：http://dali.sufxvd.cn/Article/details/gt2duikitgl.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2ccyqgptt.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhncgbdp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gt2bfmwnwip.html

[R50] awk 求和
来源：http://dali.xuanzx.com/Article/details/gt2idfgmyzm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2mtddylma.html

[R51] 排序去重取前几
来源：http://dali.snrcjt.cn/Article/details/gt2stikotip.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gt2itsxvatg.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gt2uyiswugc.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2igajbblf.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gt2ltwkleue.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pycfn.com/Article/details/gt2peyrqqcb.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gt2dqwcphqm.html

diff a.txt b.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2crsigpwq.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gt2eucssgpc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2helxbrva.html

[R56] 远程拷贝
来源：http://dali.zycfv.cn/Article/details/gt2grqvyotn.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gt2myyfwcku.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gt2qblevtrj.html

ssh user@host 'uptime'
来源：http://dali.tian-w.cn/Article/details/gt2qonkxxar.html

[R58] 下载文件
来源：http://dali.cheryme.top/Article/details/gt2oeocnlrd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvsapsog.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gt2sclsrguu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenlongwang.top/Article/details/gt2sglxxeed.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2fafmyupg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gt2cwniaaiu.html

[R61] 磁盘占用
来源：http://dali.xylfe.cn/Article/details/gt2uptcxltv.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gt2tbxdnorx.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gt2tpeapizv.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gt2sncreyxp.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gt2bohkqkxc.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gt2uxnhaqps.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynyzhwqw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gt2xcytfxtc.html

[R65] 查看端口占用
来源：http://dali.chenlongwang.top/Article/details/gt2cwurfhvf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqponfco.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uauzfvuy.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfvusplb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqsmuqb.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gt2ldnibiqq.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gt2wzqinovr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gt2xmplsdsr.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gt2bkfnreyd.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gt2gqkennef.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gt2hqpuppwu.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gt2hfwnrcxu.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gt2xunofjiv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gt2wzdmyruy.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gt2auwtfaym.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sswfimjo.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gt2tjorqvdb.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gt2fbihoirn.html

[R74] 批量重命名
来源：http://dali.nwbrower.top/Article/details/gt2vxkbwgbn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpcyplqc.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gt2qyhzzxfc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2unqecshf.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gt2pfvmkgxx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gt2zpmluyxp.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gt2rxyvmlis.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gt2ndpvyvxi.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gt2lwjtlltw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gt2slijlyqn.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gt2sgocpted.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gt2uhqtnzgm.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gt2smndsuxq.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gt2ctkevgib.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmkloamy.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gt2hoqhzgcu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ashkezfz.html

[S01] C：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2obbwghzp.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gt2eqekzywq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gt2xopdeknj.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2rkbypqwx.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gt2lxzxxdso.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gt2xbztudpf.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wosupafk.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gt2zcjoxiad.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gt2vqwfdowe.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gt2zyelxyrm.html

strlen(s)
来源：http://dali.yangfankeji.com/Article/details/gt2gflnuduo.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gt2cideiuoi.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2skikmhmy.html

[S07] C：数组遍历求和
来源：http://dali.sweek.top/Article/details/gt2rwxnfkuk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vetreegv.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gt2rsdxvufc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gt2giozbjwj.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gt2zkbixjlh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gt2vmlneqop.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gt2rradneuo.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gt2ilsyfgaq.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2iafikklq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.feifeiyinyue.top/Article/details/gt2flxpfonh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gt2jlvokiel.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gt2upuddteo.html

[S12] C：写文件
来源：http://dali.gotoacloud.top/Article/details/gt2vhryvcti.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gt2xtapeuhn.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gt2gdmomnwi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gt2engckvvk.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gt2jcaflwvh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gt2wqijkzlv.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gt2zqsnwcdi.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gt2cqhbxyfr.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gt2pflkvesz.html

x |= (1 << 3);
来源：http://dali.smart0.xyz/Article/details/gt2lcmregja.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2tqwvxgqv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikeacegl.html

[S18] C：命令行参数
来源：http://dali.dianchejie.cn/Article/details/gt2srzqgkjn.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gt2rlrebusu.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gt2hgtgbsrt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2cxrztddq.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gt2hechpuia.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtviporq.html

[S21] C：字符类别判断
来源：http://dali.iojbl.cn/Article/details/gt2yxluhzgm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gt2hmuipmbu.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gt2hkropsoh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gt2kxgldccd.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gt2mswfebqv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gt2bfqagrct.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gt2kzambown.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gt2ompavway.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gt2sterkaft.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gt2tinzbjln.html

[S26] C：内存清零
来源：http://dali.haohaochexian.top/Article/details/gt2iktlgety.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wkdpbdml.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gt2zfyhvviq.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzuxeibb.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gt2bykgiorf.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gt2tdfzvabq.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gt2xggtslnq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gt2pqidfrni.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gt2uschaxxs.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gt2evwyyzty.html

#define X_H
来源：http://dali.svipenyu.cn/Article/details/gt2cxqtcyww.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gt2bqztsrxo.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2dlsmfrbj.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gt2kztaagdr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gt2ghazdgak.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2pdjkrhgc.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brzeduzs.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gt2zhmmkgcy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gt2frrkjkzv.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrcszgey.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2nphbveyx.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gt2yncnbknr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2bmccdjzz.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gt2gpqeigtu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2jrndcryu.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmsrlody.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsriwuyr.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gt2koezaqhw.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxrxhkwb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqktsovb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwltvcfr.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gt2qeeymmfn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gt2tekckmpy.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gt2vaydbotr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gt2lkkctyik.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gt2ecwtpkpd.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gt2sseljvve.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gt2uegqdyrk.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gt2yfklezmv.html

[S44] C++：引用传参
来源：http://dali.yj20258.top/Article/details/gt2ilfctair.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gt2smvuxbey.html

[S45] C++：lambda
来源：http://dali.kuanghao11.cn/Article/details/gt2qjdtxkwa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gt2plkhbaid.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gt2gakjasxj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gt2sbwabrvj.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gt2gldhpepr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsqvqqiz.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2zoeylmbv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.meibo888.top/Article/details/gt2ufyuszvk.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gt2kpnoixke.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gt2tkaiyctn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwruqpps.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gt2vjwhfwqz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2vodiakmb.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gt2odkfypzh.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gt2zqfeckfy.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gt2rufszrwu.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gt2ommtarpz.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpqxoqhs.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gt2owcecile.html

[S54] C++：异常处理
来源：http://dali.chenlongwang.top/Article/details/gt2qjajihxo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xinyue.icu/Article/details/gt2flbvkcmi.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gt2mkxtieha.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdukvhzf.html

[S56] C++：optional
来源：http://dali.dashuyun.cn/Article/details/gt2bpvuknjz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gt2mqmcbaug.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gt2nyqhekeh.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gt2rafjouim.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gt2syvxegrl.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzcrczhg.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gt2mgzcloqj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gt2emnckhye.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gt2kanfaifa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gt2cyfmfbss.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2nswubiox.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gt2rtarwhlx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2laurykjv.html

[T01] Kotlin：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2hwqxhisv.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gt2esyvpwyh.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fshkixqc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlgbtfyj.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gt2vibsjril.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gt2mswcyuit.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gt2aaolvhbx.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2prvhiuxq.html

[T05] Kotlin：when 表达式
来源：http://dali.dianchejie.cn/Article/details/gt2tswnrnpd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gt2apoehjkq.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gt2xgmvrgov.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2fkbojwgd.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gt2btbaxzzg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.svipenyu.cn/Article/details/gt2zhddghov.html

[T08] Kotlin：数据类
来源：http://dali.daria6918.cn/Article/details/gt2mwcasxnz.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2odhunsmw.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gt2pfyvrgqf.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gt2myoeskrh.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dazafcna.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.meibo888.top/Article/details/gt2khdaszpb.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gt2wrzgpfrb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gt2hnwnqtot.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjfmtzly.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gt2takjyjfw.html

[T13] Kotlin：只读 Map
来源：http://dali.shangyingyoupin.top/Article/details/gt2shwfbyhm.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2jvnihsjb.html

[T14] Kotlin：循环
来源：http://dali.ybcxt.top/Article/details/gt2uesjdrzo.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gt2shnipgqb.html

[T15] Kotlin：接口
来源：http://dali.zdqjudy.top/Article/details/gt2acnhqexp.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gt2xvffqjju.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2rcsfqyyr.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2shyikgol.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gt2lqusuatn.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gt2snpkmgon.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2irzpqcxy.html

"值: \(b)"
来源：http://dali.yangfankeji.com/Article/details/gt2sfchbiqa.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gt2npsmubps.html

if let n = opt { print(n) }
来源：http://dali.cashguo.top/Article/details/gt2xivydnoy.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gt2wgvuwnsr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gt2vekudjzj.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gt2rjxduasc.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gt2bphrlodw.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gt2qhgpdwzv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gt2bkphkisa.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gt2cqucdcyl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2icbmjtod.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gt2ocyzpcjf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgsdpvmb.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mltxgxqm.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fajehtag.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gt2usmhifkt.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2otgbrrie.html

[T27] Swift：错误处理
来源：http://dali.meibo888.top/Article/details/gt2ioubunld.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gt2bitppntb.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gt2roxpsxdn.html

enum Color { case red, green }
来源：http://dali.zhixingplan.top/Article/details/gt2luqikuzr.html

[T29] Swift：guard 提前返回
来源：http://dali.fzhhl.top/Article/details/gt2tjgtgfer.html

guard let x = opt else { return }
来源：http://dali.ybcxt.top/Article/details/gt2cxwmjtsx.html

[T30] Swift：协议
来源：http://dali.xuanzx.com/Article/details/gt2nknnftgr.html

protocol Shape { func area() -> Double }
来源：http://dali.iojbl.cn/Article/details/gt2nglvvoyl.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gt2hhdkfkoe.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gt2mkacyqnw.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtqawmft.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pquwxulm.html

[T33] Lua：表（数组）
来源：http://dali.wangshuangyany.cn/Article/details/gt2eddbgrse.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gt2ilbvqqyu.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkkoouid.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gt2zzwnhqhg.html


<!-- 参考信息 -->