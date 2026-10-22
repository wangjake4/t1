代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtxozjbvoc.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffcwmugn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gtemnkfgkt.html

[R31] 局部变量
来源：http://dali.ydzc1.top/Article/details/gtxidgtaxj.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtblpvgzxu.html

[R32] 参数个数校验
来源：http://dali.c1oappe.top/Article/details/gtqscyrpvp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbfyudfln.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtfjspigit.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtwphhyvsb.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gttomprkui.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtblzugrjh.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtgesxeqkq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cqqwz.cn/Article/details/gtveyxqier.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gtpdpexjsl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtorzmcecl.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gttetqicvw.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyucmmar.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gtmnhdgwga.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gtmrpdmqyn.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gtgwspevks.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gtfiklwgfz.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gtzigsokmo.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtewrnznxm.html

[R41] 丢弃输出
来源：http://dali.andypj.xyz/Article/details/gtjmdkrhkr.html

cmd >/dev/null 2>&1
来源：http://dali.iojbl.cn/Article/details/gtdtolptei.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gtbypozvqj.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtmjixnwqn.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gtaevcfhhc.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gtvfeksknj.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtnkdoxgmn.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtbuemhsue.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtyicwxxcc.html

find . -name "*.tmp" -delete
来源：http://dali.wangshuangyany.cn/Article/details/gthrpczzuv.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gtyznawvta.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gtkhbmvhpw.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtsayxmfka.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtlovjqxdj.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gtssubtiqu.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gthazhmjkn.html

[R49] awk 带条件
来源：http://dali.xuetiantiany.cn/Article/details/gtgkaxzqqk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.quarkkingdee.top/Article/details/gtkpppadgs.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtrnobnvro.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtwpjlxejk.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gtgqbsojnt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gtzvhqhmtk.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gtmkgbvwak.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gtvdutopwq.html

[R53] 查看文件头与实时尾
来源：http://dali.sxryk.cn/Article/details/gtbuixpjun.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gtrbaehthr.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtshgqanua.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gtarakqtsc.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzzphzub.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gtirwuauvs.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gtbysrsvom.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtpnikdovs.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gtxdfcaqlm.html

ssh user@host 'uptime'
来源：http://dali.xziqi.cn/Article/details/gtywkwoyct.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gtjvdxfrlx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gtbiburmpm.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtsulfjlau.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtsvrmlviv.html

[R60] 只看 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtnamblkln.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gtzzujxvci.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtbeiairei.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gtrelknlop.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtbcaybypc.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gtjsmxqeln.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gtvtjzpljm.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gtmqchtkbr.html

[R64] 结束进程
来源：http://dali.cashguo.top/Article/details/gtofpqtmip.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gtqlogabph.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtpuixcuty.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtxzmudhvy.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtvupcoghp.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gtirpdxkzp.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gtyowqjpre.html

openssl rand -hex 16
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvjqbtzz.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gtpsopscel.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtexdklxdm.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtoaznhidp.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gtpxcqvkfj.html

[R70] 时间戳与互转
来源：http://dali.cdnleiting.top/Article/details/gttcuwctoj.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gtsixcvlly.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gtkdaiiocl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gtednovbxm.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gteriithap.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtjkpanvwu.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebdyujhp.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gtgjqztxwk.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtbeewmzbb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtrkndtpal.html

[R75] 导出环境变量
来源：http://dali.cqqwz.cn/Article/details/gtxibxihjf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtcxnmgwxb.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtgkqgcrvd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtyhwfszhj.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gtnxvhafev.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbodrgib.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gtfyywvdue.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtspxazhwo.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gtejhockpf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gtcaeuaoki.html

[R80] 查看脚本执行耗时
来源：http://dali.redwolf501.top/Article/details/gtvumvaspu.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gtpmidkhwt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmnieoxcl.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gtfioyzoiv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttbrlgfrt.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gtqkqjhkmp.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocqpvpvt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtbonhjded.html

[S02] C：变量与格式化输出
来源：http://dali.jyoumei.cn/Article/details/gtzpwclxpc.html

int a = 10; printf("%d\n", a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrbcjchx.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gtmrnwadnq.html

int x; scanf("%d", &x);
来源：http://dali.zdqjudy.top/Article/details/gtbscirdoo.html

[S04] C：字符串复制
来源：http://dali.yonumen.top/Article/details/gtesjrqzeq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gtffcchnet.html

[S05] C：字符串长度
来源：http://dali.jianghu66.top/Article/details/gtzkzhulgn.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gtgrgehayd.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gtsxrjrpue.html

strcmp(a, b) == 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebhrndfv.html

[S07] C：数组遍历求和
来源：http://dali.sweek.top/Article/details/gtpdlqjkfl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gtkpkdkxja.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtbglrvszq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gtoignktsq.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gtpeopntol.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gtbrdpcvzg.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gtoictoazf.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gtistknehy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtolrkfruk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtxthcqryp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gtqpyaipui.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gteadiqcpx.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gtyujyhmrp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.birdmap.top/Article/details/gtnvgfrjhv.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtodzkekyc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gtuyamyzpq.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gtrgrqmfkd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gtkrwyasdt.html

[S15] C：类型转换
来源：http://dali.yuxming.cn/Article/details/gtzwhberpr.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtanhccuda.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtpscggkqo.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gtzqhbkgsm.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtkybyewcw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aizwys.cn/Article/details/gtmolwujzy.html

[S18] C：命令行参数
来源：http://dali.guannengcc.top/Article/details/gtuchyepem.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gtflosnxca.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtdykmfcwd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtvbizkrls.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gtfmmukexl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtesiagmmt.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtloloybjh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cdnleiting.top/Article/details/gtmgrtelmp.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtlmimvfke.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gtgfcbetop.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gtiorhcwtj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yueranfly.top/Article/details/gtopfcfhip.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtxzzqyutp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gtjekoywsh.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtqgclspxj.html

memcpy(dst, src, n);
来源：http://dali.yonumen.top/Article/details/gtqrjggztw.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gtogpybnei.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtomflvanf.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gtacapmzly.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtlyocbher.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtyisvdltx.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gtjunoplpn.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gthucpxqap.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gtmciqkilu.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gtrbfswngz.html

#ifndef X_H
来源：http://dali.yonumen.top/Article/details/gtadxxwuko.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gtqzpweylw.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gtwnvzohwu.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gtabdrkfpg.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gtqlmeabhl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gttnrctwdg.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gtwkwysxmb.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gttslqqdho.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gtkqfzapyn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gtpyrosolg.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtakvfssca.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gtkfrkwwwj.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gtblnnmtxo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtzevvaisw.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtfxutopgt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtadlfhmbi.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gtwujkqkes.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtyqiieyji.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gtlhslxwzq.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtovuoyicp.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtilogksew.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gtdbubvnpf.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gthgbdhjcg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtuwbzuoht.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gtjbngwjgn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gtlavmilyp.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gtcexwwgjx.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtgghpkuum.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gtymtysvdu.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmikvfpbz.html

[S44] C++：引用传参
来源：http://dali.9152youxi.cn/Article/details/gtrhdtqdjd.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkancqyhz.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtadqfcmts.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gtpnyucrra.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gtuvdzqfvr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258.top/Article/details/gtuzgcupqa.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gtigbdzwfi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gthfxwolcm.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtkdwcnyxc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gtspifimjg.html

while (std::getline(in, line)) { }
来源：http://dali.yonumen.top/Article/details/gtlfofozij.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gtlzzjadpq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtkcwcrwnm.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gthznaoxuf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegrsnoip.html

[S51] C++：显式类型转换
来源：http://dali.zhengqikj.top/Article/details/gtbuajnasz.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gtdxbufunt.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gtfnjpuxuz.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gtzkjbuqbb.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtcwgemuwg.html

std::vector<int> w = std::move(v);
来源：http://dali.hammf.cn/Article/details/gtwtmwnnzh.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtldjlkdol.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtxoutsdih.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gtqlthsaei.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gtglcpxjdw.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gtktftcbli.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqpubzoa.html

[S57] C++：编译期常量
来源：http://dali.yongpay.top/Article/details/gtbhzaphmm.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtigrfpyhl.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gtclzfayct.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gtcxzkcrzz.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gtiubxkhhk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gtlfmukuzn.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gtmjkpxhru.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtlqgdtjyi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbsyxbhix.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolclotuo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfedyaxwd.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gtfxdafhan.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtfyaezzqx.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gtlfymnydl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtgbgtlttb.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gtepmwwmpz.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtoibkxmzg.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gtibreihyr.html

val n: String? = null;  n?.length
来源：http://dali.smart0.xyz/Article/details/gttnkoftoe.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gttzycajij.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gtojvkdbdz.html

[T06] Kotlin：集合映射
来源：http://dali.316326.xyz/Article/details/gtzcpprzpa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtbgslmirr.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gteawdikpg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtojfcqotk.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gtubklefxe.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gtiblnbfkr.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gtvcywxnkd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexwojsty.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgghrclk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gttedivnfv.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gtaotfqfas.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gtfqrbkbim.html

[T12] Kotlin：解构声明
来源：http://dali.316326.xyz/Article/details/gtejrobjpp.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtqmdjjcgj.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gtrskikfbk.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gtrhkzqoba.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtcucxjevd.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gteptvgwxw.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtfywtebnp.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gturwhzozp.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gttvpboduh.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtwwogssym.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gtingyufso.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtfxyeccvn.html

[T18] Swift：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanxkzhnd.html

"值: \(b)"
来源：http://dali.birdmap.top/Article/details/gtduydckmk.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxvkcvlm.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gtixsaeqzt.html

[T20] Swift：数组操作
来源：http://dali.hywenlv.cn/Article/details/gtidgilryz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gtodtbopck.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gtyjuathut.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gtnuwptacm.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtygqsyktz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gogol.net.cn/Article/details/gtqwprqxnx.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitddorrp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtaczxlawq.html

[T24] Swift：闭包
来源：http://dali.cucudq.cn/Article/details/gtjimxkwha.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtbqczwdsg.html

[T25] Swift：结构体
来源：http://dali.dianchejie.cn/Article/details/gtlzbldyfv.html

struct P { var x: Int }
来源：http://dali.hammf.cn/Article/details/gtczxjyclg.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gtjqzkxpfg.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gtkhqnkmno.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gtnntoahuu.html

do { try f() } catch { print(error) }
来源：http://dali.fengsongda.top/Article/details/gtbvwkqizu.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gtcnphqbwt.html

enum Color { case red, green }
来源：http://dali.shzxlz.cn/Article/details/gtywoytlkr.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtgftrumhz.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gtltkovqrp.html

[T30] Swift：协议
来源：http://dali.jianghu66.top/Article/details/gtglswwfnb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhixingplan.top/Article/details/gtratzycgm.html

[T31] Lua：Hello World
来源：http://dali.yongpay.top/Article/details/gtssvhtduj.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtejxirjqq.html

[T32] Lua：局部变量
来源：http://dali.zycfv.cn/Article/details/gtcfwmzaba.html

local a = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtwvgrxgyc.html


<!-- 参考信息 -->