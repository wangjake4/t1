代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gtmukvghpe.html

[R26] 命令替换
来源：http://dali.xuetiantiany.cn/Article/details/gtlifwpwon.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimcrhjaq.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtnnnissin.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgctzlcn.html

[R28] 浮点运算
来源：http://dali.jinghuilouyu.cn/Article/details/gtpruqztyd.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gtkdfossav.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtocjniszi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gtosddqjax.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gtsfscqbxv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtmnhganjr.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtiuaabynr.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtwyybohwo.html

[R32] 参数个数校验
来源：http://dali.hnxiangtu.top/Article/details/gthoqxruhy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtlyqdbzff.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gthmciiiic.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gtonpbxijh.html

[R34] 退出时清理
来源：http://dali.iojbl.cn/Article/details/gtlcahfnbi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtojrbxedr.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjvucisk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.0kj1m.cn/Article/details/gtcetdtkfs.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gtwmnwclov.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gttzumiujz.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gtlhbaketg.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gtdmjewimj.html

[R38] 管道串联
来源：http://dali.chenjidiqi.icu/Article/details/gtnjdkwsbl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeohpeja.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gtokfwzoqi.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtgqusnnjw.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gtrqsmcvti.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gtpxkywuag.html

[R41] 丢弃输出
来源：http://dali.ybcxt.top/Article/details/gtraxoggpy.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtvswajyqx.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gtcizxumsh.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gttsjyunrk.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gtzncoduml.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gtdyaoqaoi.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gtvjhoudvm.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gtqkjyykbd.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gtbugtnifl.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gtojmrgycl.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gtvxfewlgj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gtpbcaovlj.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gtasliptxm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gtwhunfymg.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwezfpsgs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gteocwulxe.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtxlqxurxk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtotgkgsvy.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbjklkax.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gteitbalrw.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtysatmvsv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.vqdsnc.cn/Article/details/gtygtlteda.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gtpbzxpngk.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtlojeqpnp.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gtsdqybmvq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gtkncmrrdo.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gtlqijhdmy.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtfuytzpkb.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtmlecdshy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtahaozwge.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gtxwztoogh.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtidbnvrni.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gtcxdeyqrn.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gtsyzzkgfj.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gtspkikavs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gtalxhcuhm.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtomiblexh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybqppalw.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtqbziytbf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gttkwovpmr.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtcjzcewqk.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtlhfaxijx.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gtebiflklc.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gtrupuedtf.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtqrzfgvbb.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gtflpfeori.html

[R64] 结束进程
来源：http://dali.yueranfly.top/Article/details/gtdhbuoyfs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gtfffwcoxw.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gthdqccpwl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.smart0.xyz/Article/details/gtjscsphji.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gtpqdmrixn.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtivfytipr.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtmyotveas.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gtjrtukatv.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtgnuufpds.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtkwpaqcec.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gttjsrqgfr.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gtzvdlskul.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtgpkuzcgu.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gtlqejcyke.html

[R71] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtafdbayhx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gtkwikfdak.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gtovaaevqn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtqztvpnoy.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gtxkpikkoy.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gtvgosdzpd.html

[R74] 批量重命名
来源：http://dali.hnxiangtu.top/Article/details/gtyuawvsjx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gthfnlihir.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtmbltmgtm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtxoordmga.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtlrkbbcof.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtuygjfnho.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gtmhlwascl.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gtdwrfutco.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gtclhcndkw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pengpengdd.cyou/Article/details/gtinwuouii.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gtmhccessb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtgwyjfrcm.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangtech.top/Article/details/gtnirkkfsc.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gtzottylzs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtlpjamgsy.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtfanbjhpo.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtldezxawz.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtbjounqbj.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gtyuuwushy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gttzgbniar.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtjewqiijr.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gtsjufnoyn.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gtytsdjusb.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtdjzdmakn.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gtnypwaoxc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gthwerhlnt.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtmpgylplr.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtnaguwake.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtewtfunqo.html

strcmp(a, b) == 0
来源：http://dali.feifeiyinyue.top/Article/details/gtxysytysa.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gtexotxoad.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gtnssmgbku.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gtrixkoxuw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gtxecykxch.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gtninecioh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gthywurjje.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gtwjnxjngx.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gtqnmfsxbb.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtpbwmjfoy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gtxfxaogqp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xinyue.icu/Article/details/gtbxmmgohs.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtynlyrmna.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtbyvtljsn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtctaikdcv.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtosswlbzi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gtzurqyqwn.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gtmpophjzo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fengsongda.top/Article/details/gtkjenidau.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtcslkawhs.html

(double) a / b
来源：http://dali.hammf.cn/Article/details/gtxfvygfzi.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gthaadiujv.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gtdpgyexyr.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtfdnhnmuj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtrwzgohnq.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtfkojavjl.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gtqhwnpxwe.html

[S19] C：快速排序
来源：http://dali.andypj.xyz/Article/details/gtxhwnqsda.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtarhnaqxb.html

[S20] C：二分查找
来源：http://dali.hongshengwenyu.top/Article/details/gtxkfqefzu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtpttwuvqm.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gtkbjpaggo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gtmnmsrdmj.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtwgpsynwu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gtartdqhix.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gtnbvgcexz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgjvuayg.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gthlrbhtwt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gtnzznvjdp.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtdpxvrrvn.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gtgfudoerx.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gtdhaibtlh.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtuqzazfal.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gtjqicuvfg.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtstjctjzg.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtdldsywhp.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gtpsvbydbu.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gtpqdmytke.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtdhucrikc.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gtvrzltfdf.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtxprgwoso.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtwiflgiha.html

#endif
来源：http://dali.feifeiyinyue.top/Article/details/gtcxqlnewn.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gtikcebqfx.html

#include <iostream>
来源：http://dali.9152youxi.cn/Article/details/gthcrtjttk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.vqdsnc.cn/Article/details/gttxiaztru.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gtwtydjjsw.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gtmgyaobld.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gtyfgvrldv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtmnbhdiha.html

[S34] C++：遍历 vector
来源：http://dali.dianchejie.cn/Article/details/gtoqumnsiw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yonumen.top/Article/details/gtinnveokz.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gtnqijorxq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtkmmgudvt.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gttcdhtkrd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtgtkhspet.html

[S37] C++：set
来源：http://dali.yj202588.top/Article/details/gtnowrohuq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgqgoojs.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gthbiqgxmo.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtrntedjon.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gtkcxwebwr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduewcfze.html

[S40] C++：查找元素
来源：http://dali.zhoulong.xyz/Article/details/gtlgtuvfva.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtoklhquxy.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtscyiloqo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gtediitvns.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtfknmcdze.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gtvabbckpl.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gtjoiporan.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujkhrvwt.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gtogmlalch.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gtyrnmvpoc.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gtpvtrziup.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.9152youxi.cn/Article/details/gtvbigvrme.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtxxttyqrm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtpubvktkk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gteqnznbdj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gtpfidhewm.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtybbtsbcs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gtjvfekbby.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtpmptrliv.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gtaywmpezk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtflgkrpwl.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvwsguis.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gtwbzcgwmq.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gtgrjhucyx.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtmznziwlr.html

[S52] C++：const 与 noexcept
来源：http://dali.snrcjt.cn/Article/details/gtvfudxoxx.html

int size() const noexcept { return n_; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqffbori.html

[S53] C++：移动语义
来源：http://dali.feifeiyinyue.top/Article/details/gtnvjapmks.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gtoorzjzpz.html

[S54] C++：异常处理
来源：http://dali.chenlongwang.top/Article/details/gtfpucqwma.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hysaishi.cn/Article/details/gtrphmcesw.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gthbxxpsxy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ivvv.top/Article/details/gtosyvozed.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gtyujbrmqa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbeshhqqw.html

[S57] C++：编译期常量
来源：http://dali.nanxuanxn.top/Article/details/gtmzyxtdxy.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gtcafrlvkl.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtsoqligkg.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gtdeulhylh.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gthkrzrqbj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.mhx1999.top/Article/details/gtlztnfxod.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gtooswfrno.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gttawhdbvh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvosugbvb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtyvtneoym.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzufkpgey.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtjfsronhv.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtfhxhtuvz.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gtnohmtpfk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gtbsjuiaia.html

[T03] Kotlin：字符串模板
来源：http://dali.aizwys.cn/Article/details/gtkeacskmv.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtwuwovfnn.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gtacnvyrgx.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gtzpfqglfc.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtggzgixms.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gtiiflroax.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gtcugnscbq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtuoammufv.html

[T07] Kotlin：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtmgrclrcm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gtlxxfadcn.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gteinfxrlz.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnogqzao.html

[T09] Kotlin：扩展函数
来源：http://dali.cqqwz.cn/Article/details/gtjghhyhqu.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gtqtbwcpki.html

[T10] Kotlin：默认参数
来源：http://dali.ehwqpu.com/Article/details/gtkwinaxpx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gtpzrjjofp.html

[T11] Kotlin：协程
来源：http://dali.sysykeji.top/Article/details/gtjlrhapll.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj202588.top/Article/details/gtswyazuen.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtafiyjhiu.html

val (a, b) = Pair(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gthxvyuofs.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtjsohqmsf.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gtlojonpjm.html

[T14] Kotlin：循环
来源：http://dali.zhoulong.xyz/Article/details/gtnwgkuvxp.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrcwzrrb.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gtcjxcewdm.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtxwqqkosb.html

[T16] Swift：Hello World
来源：http://dali.bjfxy.top/Article/details/gtixapvoqh.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtkcpifzvx.html

[T17] Swift：变量与常量
来源：http://dali.jinghuilouyu.cn/Article/details/gttifmjvlw.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtwgiizqdr.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtjivcecvz.html

"值: \(b)"
来源：http://dali.yj20258.top/Article/details/gtrdzyphda.html

[T19] Swift：可选绑定
来源：http://dali.andypj.xyz/Article/details/gtilcskate.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gtsgcnzyks.html

[T20] Swift：数组操作
来源：http://dali.sufxvd.cn/Article/details/gtujmjtgav.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtfgbrzshr.html

[T21] Swift：遍历
来源：http://dali.sysykeji.top/Article/details/gtidloyghf.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gtwwhwbthz.html

[T22] Swift：字典
来源：http://dali.zhiwuduotai.top/Article/details/gtmpxxnncf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gtxhnwwwiy.html

[T23] Swift：函数
来源：http://dali.xziqi.cn/Article/details/gtiwxfizct.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtgyakopsv.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtsdzwayro.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gtukxgxsyi.html

[T25] Swift：结构体
来源：http://dali.chenjidiqi.icu/Article/details/gtgfuipyeo.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gtuaubwael.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gtadnzmkuf.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gtieyudqic.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gtzaaoulev.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gtciqvddqw.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gtrqsoiwwk.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gtdmqqzaya.html


<!-- 参考信息 -->