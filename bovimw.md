代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gtqoeukvwz.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gthgbelnms.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtiyfaqwrd.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gtyglacjxo.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgecotzat.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gtmdphduil.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjaxowzzh.html

[R33] 捕获错误并提示行号
来源：http://dali.mhx1999.top/Article/details/gtudekblwh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gthrlnedui.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtqgifafqd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtxjnbxulu.html

[R35] 后台执行并等待
来源：http://dali.chenlongwang.top/Article/details/gttclrwaik.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gtfluqdlom.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gtpfyoheko.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gtvauehgct.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gtvygfjdoh.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gttnjkomvd.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtfkinjizy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtcnthdikq.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gtcscrhcuh.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtraobgzgr.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamlptdke.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gtetuqcdsd.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gtqqkjadyp.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtyaxmttir.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtyvyamuxj.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrqesbog.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtbwmdtzca.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtxtzecgfa.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gtsvdblqhs.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gtahcwsgzz.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtmnbnnnce.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtkxaqbhto.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gtveyvjtoc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtsmgegczu.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtcurripio.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gtjzqzsbqh.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gtvfxzxxex.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtlsmccjal.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gthrcnndrk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gtdpkzmodp.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtsivsbira.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtpzmickie.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gtoghqasie.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gtssjywopq.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gtckrlanff.html

wc -l a.txt
来源：http://dali.xuanzx.com/Article/details/gttccfxjlq.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gtozcjqjip.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gtlmvpcxeo.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gtxvvebdzk.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gtwwvqjkcc.html

[R55] 压缩与解压
来源：http://dali.havefunace.top/Article/details/gtucmrtyne.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gtzdyyufmd.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtqigvlgdr.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gtzrxzdihb.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gtxunmwfkr.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gtxbmtabjc.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gtnvjiioeb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zycfv.cn/Article/details/gteyblunop.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtaxcfeydu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gtzbuuowou.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtzborthva.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gtdizzxjuj.html

[R61] 磁盘占用
来源：http://dali.shangyingyoupin.top/Article/details/gtcsugrtyg.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gttvmnhxvz.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gtumqvtdyi.html

du -ah . | sort -rh | head -10
来源：http://dali.hammf.cn/Article/details/gtmcjuqgiv.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtxdsjwytr.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gtqsnsegnw.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gtljekqtzp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtxphznlze.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gtfravphlc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gtlmjrwdtv.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtvmcjyvme.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gtyeedrikf.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gtffozzyyo.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gtxrijoyrf.html

[R68] 计算文件校验值
来源：http://dali.cheryme.top/Article/details/gteiamhlrt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtcufclusb.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gtwhijdiqq.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gtesbopfiq.html

[R70] 时间戳与互转
来源：http://dali.daxiang520.top/Article/details/gtsngdryed.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtpngutwuc.html

[R71] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gticsyyvtg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsvgxzmm.html

[R72] 等待端口就绪
来源：http://dali.jyoumei.cn/Article/details/gtyvbhcdif.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtyivukerg.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gtjaijwpfr.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gtnzwsyjax.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gtlbdxjmby.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gtuolvuajk.html

[R75] 导出环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtbautrgta.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gtturumzow.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gtlhegfkex.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gttxcaqufs.html

[R77] 读取用户输入
来源：http://dali.ivvv.top/Article/details/gtdbygknui.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangtech.top/Article/details/gtourlyocr.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gtlhrmejmj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gtrzkjetom.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gtbvilqcwa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tian-w.cn/Article/details/gtttbuimbh.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gtmoyofgei.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gtkykjaijv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtezyqprvm.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gtqqypahjt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gticeqavff.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtzrsxguuc.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gttkkxhoes.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gtgfgmxtxa.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtinbvmmmj.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gtilyzeoqd.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gthjopkihb.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gtgecyxpry.html

[S04] C：字符串复制
来源：http://dali.xuanzx.com/Article/details/gtffbjlllw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gtyqrsxgtv.html

[S05] C：字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtevmcvidn.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtouqzuxks.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtbnpprphy.html

strcmp(a, b) == 0
来源：http://dali.hfpthk.cn/Article/details/gtikkxiurr.html

[S07] C：数组遍历求和
来源：http://dali.chenjidiqi.icu/Article/details/gtmxnlfyrw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gtthqfheqw.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gtxfvwbdua.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhaamwrm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gtctoszdmm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gtovixokyn.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtehdscvxn.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gtdagurxck.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtnprfgmlq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gtqrmnpogp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenzaomai.com/Article/details/gtarpljxpj.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtjfakapwf.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gtldrqjqtj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gttqhzlzyn.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gtalknuvqz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gtbrwsmmlz.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtvkmvmrtx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gtbapddbmu.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gtgbkdysvv.html

(double) a / b
来源：http://dali.jinqigufen.top/Article/details/gtfgrsrabs.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gtrdbykjkj.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gtkuxhqlcc.html

[S17] C：安全拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtgbcsvdza.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fzhhl.top/Article/details/gtlkdtbdsf.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtxvlajxpw.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtkvltfkin.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gtnbqewvtg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtzxmnykjt.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gtyilzpahe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtglphyoqz.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gtmbpxmgvi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gtpqheqveb.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtevrsyzrr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gtcixoaykd.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gtpsffkyvj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gtloeejdig.html

[S24] C：获取本地时间
来源：http://dali.jqgufenzy.top/Article/details/gtyaadgtdl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gtvpqmxrkx.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gtiumwybqr.html

memcpy(dst, src, n);
来源：http://dali.quarkkingdee.top/Article/details/gtdlwrhfbt.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtxtlylloa.html

memset(a, 0, sizeof a);
来源：http://dali.dianchejie.cn/Article/details/gtfielpmqf.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gtypkaubwp.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtwsihvmns.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gtipxfgtqo.html

static int counter = 0;
来源：http://dali.gogol.net.cn/Article/details/gttqktbhyx.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gtablzkijv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gtuolbamap.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gtjqpmgvsz.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtqlnszudg.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gttoflhsxt.html

#endif
来源：http://dali.gzhubu.top/Article/details/gtgzvmassh.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtofdnlzot.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloqivpzc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtncvdvjxm.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gteafiihtf.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gtbpouauet.html

[S33] C++：vector 增删
来源：http://dali.ehwqpu.com/Article/details/gtyfcfrfuz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtlpyfwwre.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gtsatejvkj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtaovrfsgl.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gtpoupbihg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtltxcfbhy.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtiqfkizpw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtyhpywvzi.html

[S37] C++：set
来源：http://dali.cucudq.cn/Article/details/gtwssfxniq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tianlin.xyz/Article/details/gtitsopvzp.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gtefztmwag.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gtnlezwdem.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gteoseffvz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtxbhdzvzf.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gtsbbfhpdv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gtpabrnykq.html

[S41] C++：类与构造函数
来源：http://dali.yonumen.top/Article/details/gtwynajjqx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gtpqcapesw.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gtigplighc.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gtvetnubhj.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gtvbzjtdsy.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gtzcpdchos.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gtnefkwepp.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawvhnxug.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtjypgaply.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gteyqilfmi.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gtdpnrpmwj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gtjdyqzuou.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gtspbdbxva.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gtewmgzzfx.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtpqddjdmx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gtnzwndoov.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gtcfsxmnmw.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gtbzbouans.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gtpgmfszdk.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gtzvwizuoj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtxotzrmsl.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtydvnhcss.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtyhiykfdy.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gtnmdsothn.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtfvohizdo.html

[S53] C++：移动语义
来源：http://dali.zycfv.cn/Article/details/gtglavhhiv.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtfdaqmvcq.html

[S54] C++：异常处理
来源：http://dali.hnxiangtu.top/Article/details/gtqghngxbx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtevowyddw.html

[S55] C++：结构化绑定
来源：http://dali.zycfv.cn/Article/details/gtibkrrrkq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gotoacloud.top/Article/details/gtabrmtzgc.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtgeyjtgit.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtctrtxwpl.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gtogexgarr.html

constexpr int N = 10;
来源：http://dali.xuanzx.com/Article/details/gtoxifrugj.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gtogtltnym.html

namespace ns { int f() { return 1; } }
来源：http://dali.guowangkeji.top/Article/details/gtawvpjlor.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gtprtygrfw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shzxlz.cn/Article/details/gtvsukmfvv.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gtqmntfijd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtnxcwwvki.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthkpwozmw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtjmemizqn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyqwczieq.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtkhlrlhgt.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtvywzoudu.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtqqjcvicx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gtycjrwwyn.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gtcfskmjnl.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtaqammrrh.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gtpjtngsfi.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gtexqsrxys.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gtcxqslivh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gtxvbagtaz.html

[T06] Kotlin：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gteumzvfwf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtjrdnqndr.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtmuagpexm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtsggcwspw.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtntumqcbp.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gtjrdmbrqk.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gtfjytmdve.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gteznnjxgf.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtzqpkemmc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gtawbgdsxd.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gthynkmkpi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gtcjjkqitl.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gtgdsiqzpl.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtcrticcds.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gtkwlgjqbz.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gtzdabfogq.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gthcmxznxf.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gtgrmbuexy.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gtuazvwvyl.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtairrndpi.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtubaaxliu.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gttllmeimh.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gtbstdenjf.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gtmebnysak.html

[T18] Swift：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtxbnfygwj.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gtzoihahhy.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gtihbkqcsh.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gtzkxbgagj.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gtcksozrcs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gtqcgogtzb.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gtrfxragxy.html

for x in a { print(x) }
来源：http://dali.zycfv.cn/Article/details/gtvxewsxhk.html

[T22] Swift：字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbynxzmh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yangfankeji.com/Article/details/gtlnqbjukw.html

[T23] Swift：函数
来源：http://dali.ybcxt.top/Article/details/gtvjjkjshh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgfzy.top/Article/details/gtguypcmrg.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtgblpnnqm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtnrqyekxw.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gtkuzdmssv.html

struct P { var x: Int }
来源：http://dali.zhixingplan.top/Article/details/gthqjmvydl.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtbvkujtwc.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtcphbosgz.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gtkgenhghp.html

do { try f() } catch { print(error) }
来源：http://dali.chenjidiqi.icu/Article/details/gtqbpcuwkc.html

[T28] Swift：枚举
来源：http://dali.yongpay.top/Article/details/gtzjebxqty.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gtlefaxahw.html

[T29] Swift：guard 提前返回
来源：http://dali.sxryk.cn/Article/details/gtzixafflc.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gtiqrcihyi.html

[T30] Swift：协议
来源：http://dali.quarkkingdee.top/Article/details/gtblyxidjq.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gtrpbkkpbz.html

[T31] Lua：Hello World
来源：http://dali.yongpay.top/Article/details/gtzvscrmaz.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gtqisjijsc.html

[T32] Lua：局部变量
来源：http://dali.jianghu66.top/Article/details/gtjtjpfddt.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gthjjpfutk.html


<!-- 参考信息 -->