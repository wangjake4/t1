代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtcsjzemwe.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtpohrbsiq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtfazsykzc.html

[R17] 数组定义与取值
来源：http://dali.yj202588.top/Article/details/gtpdcigebw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gtbvzxzuoz.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvsqpqno.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gtxjqwbnan.html

[R19] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspvdduej.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtdmrudgby.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtdzbieytn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gtlmaqpxok.html

[R21] 字符串长度
来源：http://dali.aizwys.cn/Article/details/gtuloyzgbd.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gtdaiqzmle.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gtzxzilgio.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gtowukigoh.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtxjkezbvi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtheoxjtep.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtyvnrlbfy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gtbrfrjcoc.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gtzxvugovj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.vqdsnc.cn/Article/details/gtrdpsrxvm.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gtusoarsfl.html

now=$(date +%F); echo "$now"
来源：http://dali.guowangkeji.top/Article/details/gtffnqnusr.html

[R27] 算术展开
来源：http://dali.hammf.cn/Article/details/gtakzqrxyn.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtvkwualtc.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gtwgflehnc.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gtqunvuzhl.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gttjtybluh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtvlqldmef.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gtfpsgoswb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gtvjvfwsbp.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxjokqhl.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtkrgvflwj.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gtxrgeguuu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtarmyzxqd.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gtjihwmctw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gtoyjmdzqh.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gtnijizcnh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtqfkzhdyk.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gtpjmpksko.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jyoumei.cn/Article/details/gtdcbnktpm.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gtsxhqthal.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gttyownpyl.html

[R37] 把输出赋给变量
来源：http://dali.shangyingyoupin.top/Article/details/gtuewvbjak.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gtvlknyrgi.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gtckrqkqea.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtgxlixbjg.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtepkxtktr.html

cmd > out.log 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gttpbowlwf.html

[R40] 追加写日志
来源：http://dali.zhengqikj.top/Article/details/gtkrfsmvuc.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gtedsawczx.html

[R41] 丢弃输出
来源：http://dali.aizwys.cn/Article/details/gtsigqetrg.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtfonmtpwv.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetcrnppg.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gtrkjhwyej.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gtjgdmmhuj.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gtgpvzajha.html

[R44] 按修改时间查找
来源：http://dali.sxryk.cn/Article/details/gthtqexnzz.html

find . -mtime -7 -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtatbwpdeo.html

[R45] 批量删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwzcpefi.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gtttxegzjh.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtnqqrlcjb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gtzhybwqgl.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gteodlpvqr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtbqkrujep.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gtxgulmqcl.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtcxevksha.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtzvbxvyoq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.birdmap.top/Article/details/gtnhyszuik.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gtzhiwlguv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtwshiybvk.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtoaxcpxhx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gtozaflnsj.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gtdtkhvmzr.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gtjnmbwzns.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gtzewsikgk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtaeabrvnq.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gtbiysbrrb.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gtanzcztmf.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnbvpqfr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gtgimodwdr.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gttnxwfvui.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gtnaaiczsp.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucckjbgq.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gtroiilunl.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gtsactccrh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gtstjmvuui.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtqwjforfb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.kuanghao11.cn/Article/details/gtfblrhxtf.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtvlkrnwmn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.mhx1999.top/Article/details/gtogacjczp.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gttltcgbuc.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gtqturivyh.html

[R62] 找最占空间的文件
来源：http://dali.316326.xyz/Article/details/gtlfihqpln.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258.top/Article/details/gtoanrdolq.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfifgmpi.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gtieiwajsr.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gtdshcticn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtairacexy.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtzftdrmor.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gtcjehvmmj.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gtptiaxilz.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtpqyvccbi.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gtbceywsle.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gtrnytzyzk.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gtvhzqxnof.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ehwqpu.com/Article/details/gtffixsiqk.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gtsgqwuogx.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtypvafobj.html

[R70] 时间戳与互转
来源：http://dali.jqgufenzy.top/Article/details/gtpcxefkpa.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gtxtgbbran.html

[R71] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtqrcvztrx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtawuesgep.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtthockymd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtgkxlyuqd.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gtyelbbnyk.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gtcvrsqxet.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtcanoiwxe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gtciuolwrx.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gtflszzeyy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yvedp.cn/Article/details/gtrczngvww.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtokbqwvae.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gttxrtsclm.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gtmpnaxzes.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gtnwdjujio.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtwkzzqmco.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gtgmlzgszc.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gtqcqomobm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtxhawsvcb.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtguatlnxm.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtglixjase.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvzfxaqsh.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gtmiybjhir.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtexcpggyi.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gthrxtygal.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gtckjxgysb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gtyupgzbmx.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gtyvyqjibp.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gtrlqeobtz.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gtszifptrh.html

int x; scanf("%d", &x);
来源：http://dali.yvedp.cn/Article/details/gtcmeemwvf.html

[S04] C：字符串复制
来源：http://dali.c1oappe.top/Article/details/gthimxapjo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gtysqkgvhr.html

[S05] C：字符串长度
来源：http://dali.xylfe.cn/Article/details/gtyqzatyuj.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gtxtepwtqd.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtessvsvxm.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gtkxhubbee.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gtwpgsqchb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtkvelujwo.html

[S08] C：动态内存分配与释放
来源：http://dali.sxryk.cn/Article/details/gtgosuxyef.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gtqmyfpcbe.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gtmxbbfjsl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gtofaerlyn.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtyujdlfwf.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gtrsfrqjfz.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtwwazhsgi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gtlkvorwhn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gtynwhcovy.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gthqkhsymx.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gtyqfnvyeu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbovwzdsz.html

[S13] C：宏定义
来源：http://dali.gaohongyu789.top/Article/details/gtweidyykg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthofzevzm.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtcmbqaycj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtzyqayuvh.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gtfvxjdbtb.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gthckpqhzg.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gtgieixzeh.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gtlrkxkbof.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gttfpvmlua.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gthtpjhigu.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtbevoakux.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gtlresqdlu.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gttxtljjws.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtzyelhuop.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtldrbahzw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtgsccutmg.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gthtzgyzsb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jianghu66.top/Article/details/gtnewdjckf.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtdwwpibhy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gtnrqnfhjh.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gtjwsfjscg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtaexqpcwc.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxltorbjm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gtpnhfbjoh.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtewumxdcy.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gtpjlmsger.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtqgkbgnhr.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwmtatgn.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gtghlpduvv.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtaexlghao.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtbtvjplfe.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gtdafqokuf.html

[S29] C：变参函数
来源：http://dali.shzxlz.cn/Article/details/gtbocxpfbs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gtomlodtcj.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gthkwfyuiq.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gtkupryveq.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gtownvlwtn.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtsfmrhyve.html

[S31] C++：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtswqtxxyc.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gtdwtjchqd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gtfrmrmamo.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gtrabnirbp.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtfisbcymm.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gtbjouzvhz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtcdchpljf.html

[S34] C++：遍历 vector
来源：http://dali.ivvv.top/Article/details/gthsnrnpem.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gtvgwnzcrb.html

[S35] C++：map
来源：http://dali.hysaishi.cn/Article/details/gtmqlfbgxg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtytnkzjgg.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gtaanvkbov.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtvzhojboz.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gtxrccvong.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gtcwawmccu.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gttrjyuxar.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtmsinjwnc.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gtwbiowsvv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gtkdkhbnln.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gtnplffjrv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gtpofembth.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gtzrchoahs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.havefunace.top/Article/details/gtsgckelxq.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gtkuqlaves.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gttqxlpuxh.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gtvrvyzwxz.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gtgbmbvxxa.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyskduhxs.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gtpqxnoofs.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gteyxuxcbd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gttjxnlayi.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gtbwrqgghf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cucudq.cn/Article/details/gtggvawnvz.html

[S47] C++：结构化绑定遍历
来源：http://dali.fengsongda.top/Article/details/gtorthxayh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nwbrower.top/Article/details/gtgrtkbrlk.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtoorevdav.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jyoumei.cn/Article/details/gtzbxvljdn.html

while (std::getline(in, line)) { }
来源：http://dali.ybcxt.top/Article/details/gtayrdtodt.html

[S49] C++：写文件
来源：http://dali.svipenyu.cn/Article/details/gtfekrdxfs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fengsongda.top/Article/details/gtnsjlkgah.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gtjowoiute.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtsdbbkpec.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtnybuopoo.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtrkpvungw.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gtxtjvdhsg.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gtjbshhaiy.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtkegliboa.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtvxmkcmzw.html

[S54] C++：异常处理
来源：http://dali.smart0.xyz/Article/details/gtfipyzbqy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtfmwztnoq.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gtoznvvdqo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gtgwsjcjxj.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gtbmmwieod.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtpqfdiymb.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gtjhdutdua.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnymlulk.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gtldrwvcbj.html

namespace ns { int f() { return 1; } }
来源：http://dali.shuidangran.top/Article/details/gtsirettrw.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gthifylqdb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gtltimljsn.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafguyqle.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtjkmoxydx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtldljtplf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtooabvezy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjourtxe.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtgcbaozon.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtvjusuvjc.html

[T02] Kotlin：变量
来源：http://dali.feifeiyinyue.top/Article/details/gtwnmfysvu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gtamaarehb.html

[T03] Kotlin：字符串模板
来源：http://dali.feifeiyinyue.top/Article/details/gtynfnebbm.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gttbwptbup.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtxqsxprti.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gtgvojvhjz.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtaukquawp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkyetuqt.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gtxgfokagr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtehjdufiz.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtiacpjudp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gtsysszvsd.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gtqsambalo.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gthiodmjpj.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gtqtmkzgrf.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gtycwyqmop.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gtcairhavn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yangfankeji.com/Article/details/gtojfyfiar.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttupvetvq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tanke756.top/Article/details/gttnvmezwu.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtkluubmam.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtmkwzxniw.html

[T13] Kotlin：只读 Map
来源：http://dali.meibo888.top/Article/details/gtcohuvsah.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gtbsmgkxwq.html

[T14] Kotlin：循环
来源：http://dali.daxiang520.top/Article/details/gtjxjgjfnf.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtxfvyscpj.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gtdjminufx.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gtcawznxfe.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gtfjdpqhsv.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gttbfkdfcz.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlxvcuon.html

var a = 1;  let b = 2
来源：http://dali.cqqwz.cn/Article/details/gtgxfipcdd.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtbtfjdngv.html

"值: \(b)"
来源：http://dali.ybcxt.top/Article/details/gtbztlvlbs.html


<!-- 参考信息 -->