代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbpohzwc.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gt2hltewcal.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gt2dcufbjzz.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojpjaafe.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gt2hfvizgzu.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gt2qttqsiop.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2nabitlim.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gt2drwusghi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daria6918.cn/Article/details/gt2yofwgegq.html

[R34] 退出时清理
来源：http://dali.jqgufenzy.top/Article/details/gt2zweokncx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2ebsxaagg.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gt2dbbuqyhm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsjmseeh.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gt2wasjmsbd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigufen.top/Article/details/gt2aiwkmncf.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gt2cnegxhlx.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gt2pnkoqepl.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gt2raryzzye.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gt2ypmwmagy.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gt2kejkdiur.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gt2anfzurew.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gt2xtncyohq.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gt2zvuaapsk.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gt2xmbqwyxz.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjyltsiv.html

[R42] 输入重定向
来源：http://dali.gogol.net.cn/Article/details/gt2mqpsrjbj.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2kjkdkhxy.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrpuolsj.html

find . -name "*.log" -type f
来源：http://dali.nanxinkj.top/Article/details/gt2dximhpyc.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gt2lhsokkse.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gt2pklsyrdn.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gt2pndojktr.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gt2zjizirur.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gt2qqieyiku.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gt2dekwdmuv.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gt2tfmgwjot.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzuepyij.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gt2knvrpiln.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldgoxeix.html

[R49] awk 带条件
来源：http://dali.zhongyouzk.top/Article/details/gt2ifdlefeo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gt2hywvxwzm.html

[R50] awk 求和
来源：http://dali.redwolf501.top/Article/details/gt2azwjlqfe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2papcgcpw.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gt2yjqsvaul.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gt2syayckkq.html

[R52] 统计行数
来源：http://dali.316326.xyz/Article/details/gt2hlojzlum.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2vsdjkkyt.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gt2jxzfjemp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gt2fycsoqxr.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gt2pxjmwofe.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gt2oagukakm.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gt2ljewjsuu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gt2mjnzydlm.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gt2ycgkhzdc.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gt2lguvtaux.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gt2hpaesoyh.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gt2iphtfodi.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gt2wnwbqbuk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gt2xjtbxoja.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhqwxudk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2wekhcwmb.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2ojmvdgsd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gt2qicxvkpf.html

[R61] 磁盘占用
来源：http://dali.chenzaomai.com/Article/details/gt2etwdiemw.html

df -h;  du -sh *
来源：http://dali.andypj.xyz/Article/details/gt2lxhhdwpl.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ewdgglqz.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gt2gdkfvbyg.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gt2tcvfeflm.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gt2eyxpfgus.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gt2dqbcgzon.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gt2crwykrll.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gt2smuretjm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gt2utdozejd.html

[R66] 定时任务
来源：http://dali.nanxuanxn.top/Article/details/gt2qawdnkks.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gt2wngmjlgn.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gt2ozhlpald.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gt2btxarphl.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gt2gxpclxwc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gt2xkpywioe.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gt2faymeugs.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gt2gqxnsmja.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gt2mhlgbwsc.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gt2gpjfnvkz.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gt2yaqfsfzm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gt2svksjmph.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gt2mtxiouzx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gt2cefsrwio.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2piljyxtl.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gt2zugcgkuk.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gt2qzebtvsq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gt2pwqyurqe.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gt2vhkxmily.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gt2ojvapjkq.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gt2nyseumyj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gt2axmcdcye.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gt2ufhhpxmg.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gt2uyrfnvil.html

[R78] 交互式菜单
来源：http://dali.xylfe.cn/Article/details/gt2gzsttods.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.redwolf501.top/Article/details/gt2kmnvqigs.html

[R79] 解析命令行选项
来源：http://dali.c1oappe.top/Article/details/gt2tqjwntec.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnivvwlp.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpjdbyiq.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnudnbok.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2vtqexbwm.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prjwabyz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2wbbnhzvc.html

[S01] C：Hello World
来源：http://dali.yj202588.top/Article/details/gt2yaibdxwb.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gt2tikykhhr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ldamiepk.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2oastnoed.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gt2qjbrmtcw.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gt2givyqkld.html

int x; scanf("%d", &x);
来源：http://dali.andypj.xyz/Article/details/gt2solcymde.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsnsjzcs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2subzmeto.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2lhoywzzj.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2orrobgkl.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gt2zopujiom.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gt2dsqditnx.html

[S07] C：数组遍历求和
来源：http://dali.zhixingplan.top/Article/details/gt2zluxdqnd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tanke756.top/Article/details/gt2hapqrogf.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gt2cnxyjhpy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gt2ddfkkvkr.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gt2rubjavey.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gt2ubkikvqd.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gt2adqumbmm.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gt2udckkoea.html

[S11] C：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2xbinhzxc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gt2znbolsbh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gt2ovdvafxg.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gt2dfpfsdhk.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gt2iwkqxumt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gt2jdehxpbx.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnkssykd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2faksxnnm.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2uddpotme.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gt2pnwdmqsf.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gt2qhujsqvh.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gt2laiqrdmp.html

[S16] C：位操作置位
来源：http://dali.cucudq.cn/Article/details/gt2ryzwxroy.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gt2ruilfhdi.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2hjtnxpqf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gt2ubpljkuo.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gt2pmhdmqfm.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gt2ulcfuixa.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gt2jwrzvwwo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2ycwfqwpp.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gt2nrrbmsga.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gt2cnyufwfa.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gt2etxtdzib.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gt2cknsjnxc.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gt2afvrqaqi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gaohongyu789.top/Article/details/gt2kyraawtg.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gt2cfsgpuwg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gt2jmcucfbd.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gt2slzwyzxi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gt2pgaeqpmo.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gt2ovyzqmhu.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gt2qyuqaqrw.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gt2tldmrrqz.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gt2vphowzzi.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gt2btpvcqwz.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtqaqknn.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gt2glzyokof.html

static int counter = 0;
来源：http://dali.zycfv.cn/Article/details/gt2unqtsxae.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2nulxsbct.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gt2oelqivxs.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gt2qfhdeojr.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gt2cthhichw.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gt2ukzjtdjo.html

#endif
来源：http://dali.xziqi.cn/Article/details/gt2jjxicvqn.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2xhprvhni.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gt2bigulwop.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gt2ohvjewqq.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gt2hbabkjsr.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gt2bbbbgyqc.html

[S33] C++：vector 增删
来源：http://dali.ybcxt.top/Article/details/gt2rexbzufn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gt2lbfqftdl.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gt2ohnqdorp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gt2xpbwvfcu.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gt2slktjrdp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2aotwflyc.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncrbannc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2rtobordx.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plretxho.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gt2srozfdch.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gt2qdvphbtb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2ulgqalgm.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gt2raoskapj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gt2jbqdqbuq.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gt2hknclrgv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gt2xblbazfd.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gt2miqfybwj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gt2ixaiacdl.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gt2wvkfpxkc.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gt2zfxcnkyh.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjjskyha.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umlhehyc.html

[S44] C++：引用传参
来源：http://dali.havefunace.top/Article/details/gt2nwhozsjy.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tjxgbnsb.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gt2webgftck.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gt2waorwkwd.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gt2ynobuzom.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gt2fxwskyrf.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gt2iwlxvkvb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gt2vcfeuqts.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2ejrufxrb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daxiang520.top/Article/details/gt2qnmjwllc.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gt2fsvmprbq.html

[S49] C++：写文件
来源：http://dali.cheryme.top/Article/details/gt2blirqzcj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gt2ycbsnfhg.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjavjzea.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2euvksyua.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnhogrfj.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gt2olgoikbq.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258888.top/Article/details/gt2cvcsozqg.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gt2hvpghodu.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gt2vvuamyuq.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gt2ygxoitbe.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gt2dendqdtq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gt2wqikwxgr.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gt2fhgiuybu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gt2yeaigcaq.html

[S56] C++：optional
来源：http://dali.havefunace.top/Article/details/gt2zkhpugya.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.havefunace.top/Article/details/gt2ruwrrhcd.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gt2hrzlvxno.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2bxraohfr.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gt2wgfynhgp.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gt2wdtayyhc.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gt2keljhbjz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjkcvxpy.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gt2ccsobpxq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gt2fbjqenta.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2tcjxvusf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gt2okmiovdg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2pkhmsyhb.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2oksqephw.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2apzcgorn.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gt2nembthfu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gt2qabumqlj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmtvumni.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gt2fshuemyt.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gt2bwqtwcdo.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gt2seqnjzio.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2guuqdqss.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gt2hhzwarmb.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gt2betnelur.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2xncqcbcc.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gt2uqtoamoy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.andypj.xyz/Article/details/gt2riwherns.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gt2jutgpkzz.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gt2sbzaiohj.html

[T09] Kotlin：扩展函数
来源：http://dali.yueranfly.top/Article/details/gt2mwveducu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhongyouzk.top/Article/details/gt2ovtbelhu.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gt2wfffbskk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gt2hmlaeffx.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gt2njcwxikz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrxtynnw.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gt2barebrfj.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2ozsfornh.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gt2kkndyhjz.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gt2pinduvzf.html

[T14] Kotlin：循环
来源：http://dali.zhongyouzk.top/Article/details/gt2fxuveljx.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gt2bvevuirx.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gt2nsfjesek.html

interface Shape { fun area(): Double }
来源：http://dali.daria6918.cn/Article/details/gt2dztgqynu.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2rfuiyjih.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2juayqvrt.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gt2cxvughno.html

var a = 1;  let b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2ztvfxgml.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2ckhqcrjk.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gt2hcfhehsb.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gt2rkqvtfoe.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gt2ocgfpkvn.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gt2exjwsgte.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vpjxquyv.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gt2laaqxphw.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gt2vteqnlen.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnqgcefw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.0kj1m.cn/Article/details/gt2gnzytmfh.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2efedjean.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.redwolf501.top/Article/details/gt2zsbwcvhu.html

[T24] Swift：闭包
来源：http://dali.snrcjt.cn/Article/details/gt2xqcyyrph.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2hpfwryhc.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gt2giffceld.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gt2xgwpkdap.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gt2tgmtsqcb.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gt2llbmaxdk.html

[T27] Swift：错误处理
来源：http://dali.dianchejie.cn/Article/details/gt2ouyjfyiu.html

do { try f() } catch { print(error) }
来源：http://dali.chenzaomai.com/Article/details/gt2ytzfwloc.html

[T28] Swift：枚举
来源：http://dali.sweek.top/Article/details/gt2kqnvofxt.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gt2uqaqifhp.html

[T29] Swift：guard 提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufevnzud.html

guard let x = opt else { return }
来源：http://dali.yonumen.top/Article/details/gt2knjjsccp.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gt2fknuyucm.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gt2bwlwlwiy.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2hkzhbstg.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2tbionvon.html

[T32] Lua：局部变量
来源：http://dali.jqgfzy.top/Article/details/gt2wqwkrpfo.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gt2hstsgwvf.html


<!-- 参考信息 -->