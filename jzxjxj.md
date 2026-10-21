代发 wailian999

esac
来源：http://dali.9152youxi.cn/Article/details/gtlekpweln.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gtvmpyshgh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbusipwey.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gtwzkwiwrc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtalnyuxaw.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gthodukqes.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtlgaraceh.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtssunuhnz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtpkyucplt.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gtfgyarrmq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtgvrfzonc.html

[R17] 数组定义与取值
来源：http://dali.zhoulong.xyz/Article/details/gthlmvnuga.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gttezmbuad.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtvbwtytiy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkwofzrz.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtoicneowl.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gtqftspqml.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gtdnverwyx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gtnghwricy.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gthnlnhdaw.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gtnjdolqfe.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtoamfhnnf.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gtosmpwiii.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtjjugnaxn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ybcxt.top/Article/details/gtazxufnqj.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtikqegudp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtmojeipbm.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gtwwgixcwq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gthwssrxxo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtvyhdrnfi.html

now=$(date +%F); echo "$now"
来源：http://dali.yj202588.top/Article/details/gtsgzntdlo.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gtyfimgrqf.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gtoorssptz.html

[R28] 浮点运算
来源：http://dali.pycfn.com/Article/details/gttedhpdbd.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtjvpbpwvi.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtgogrvlxf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gthoyfsssi.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtfveqbnud.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zdqjudy.top/Article/details/gthiwvizhx.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gtdcxjoefx.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzymuwtpm.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gtcemaalqv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtsvdwdsqk.html

[R33] 捕获错误并提示行号
来源：http://dali.gogol.net.cn/Article/details/gtlmylmeyf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gttnojkmdk.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtnulukacz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtjkonmjhg.html

[R35] 后台执行并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtzpiiaovt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gtkmskoqgm.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gtcqyeycgb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtkstelxdj.html

[R37] 把输出赋给变量
来源：http://dali.shangyingyoupin.top/Article/details/gtzetnaqbx.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtvcsobfiu.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gtzjbyxbbo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gtfvcvamcy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gtaexbwirt.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gtrbdetxcm.html

[R40] 追加写日志
来源：http://dali.316326.xyz/Article/details/gtcfkdvtcd.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gthmgiivte.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtnttglepd.html

cmd >/dev/null 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtknevznof.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltivnrfi.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gthdqdnamt.html

[R43] 按名字查找文件
来源：http://dali.316326.xyz/Article/details/gtvnpimroi.html

find . -name "*.log" -type f
来源：http://dali.snrcjt.cn/Article/details/gtbxnwctrj.html

[R44] 按修改时间查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfapqgvc.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtkpueahxu.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gtwxrostnp.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gtfvuqgxkx.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gtnkckwemq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gtyifhnuzm.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gtphzlbnez.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258888.top/Article/details/gtnflrqbpp.html

[R48] awk 取指定列
来源：http://dali.hysaishi.cn/Article/details/gtouqcvqyk.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtpmgnlato.html

[R49] awk 带条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlsgwyay.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xylfe.cn/Article/details/gtjuruilri.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gtlpybmofr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtuygnzpnz.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekbjqyqq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gtqjekfwdt.html

[R52] 统计行数
来源：http://dali.shzxlz.cn/Article/details/gttzowhuob.html

wc -l a.txt
来源：http://dali.mhx1999.top/Article/details/gtihndukyh.html

[R53] 查看文件头与实时尾
来源：http://dali.svipenyu.cn/Article/details/gthxdbsdiu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sxryk.cn/Article/details/gtzfkuhdqd.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtotlszsrr.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gtmdercjwt.html

[R55] 压缩与解压
来源：http://dali.316326.xyz/Article/details/gtfmbkotpd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtxqpvjiqc.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gtugwajgph.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gtolsdakzn.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gtxhdvbkkv.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gthcvexoxw.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtmrapobhd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gtcddharwl.html

[R59] 发 POST JSON
来源：http://dali.yj20258888.top/Article/details/gtynabxuwj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtgwrtnjav.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtbildmhsf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtoknltxwo.html

[R61] 磁盘占用
来源：http://dali.aizwys.cn/Article/details/gtzgfmvxwr.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtuswvavru.html

[R62] 找最占空间的文件
来源：http://dali.guannengcc.top/Article/details/gtdslrovwg.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gtvdinqdnk.html

[R63] 内存与进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfcknrqo.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gttxqspulq.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gttcvvowbk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzifdjixm.html

[R65] 查看端口占用
来源：http://dali.cheryme.top/Article/details/gtytuyitnf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gtqxfweqas.html

[R66] 定时任务
来源：http://dali.chenlongwang.top/Article/details/gtsvrozahl.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gtlikfyswp.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gtgcvzsauy.html

openssl rand -hex 16
来源：http://dali.chenjidiqi.icu/Article/details/gtdbwodeoi.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gtohhlagni.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tianlin.xyz/Article/details/gtwtjzgxew.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gtzaqvlfho.html

head -c 16 /dev/urandom | base64
来源：http://dali.shangyingyoupin.top/Article/details/gtoarpdeqn.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gtbinrhkcm.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gtekxmwzlx.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtqqkzqiav.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtyqxpdikn.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtotbdjnop.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtlixliwgz.html

[R73] 分割大日志
来源：http://dali.havefunace.top/Article/details/gtzadobckj.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gtvgthsqwe.html

[R74] 批量重命名
来源：http://dali.jinqigufen.top/Article/details/gtaxgtkcso.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtiypuweft.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gtwjzjqbmv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtgvgjmwna.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gtizywhuvz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtdeameabw.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gturzywuoo.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtuipmedqg.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gtrgxotnaf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gttvoodict.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gtiuzuupgv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhongyouzk.top/Article/details/gtonkqtaye.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxergzje.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtculhigyu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtcmmsiolu.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gtgshgmbmk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnlggvfbz.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtnjcivthc.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gtppjggeao.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gtpjiqclys.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtqhfiloll.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtnwpcyuic.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gtaaiyoxzh.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtsgwbvvqr.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxglwjrc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gtkjjaixda.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtbeszkogg.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gtsqjvlzwt.html

[S06] C：字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfdtxruw.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gthbkcffru.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gtowlnruoj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.c1oappe.top/Article/details/gtdcgygklv.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gtupblkjpj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gtobswzuja.html

[S09] C：结构体定义与初始化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrqepmze.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gtgwnzktvj.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtjhkviiip.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtrwtcykuy.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtzvzykixm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gturkaijkj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtjhquzkyv.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbtzirff.html

[S12] C：写文件
来源：http://dali.yanxiufei.cn/Article/details/gttzxvdcrj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtkvkkliae.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gttdvnwadc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gtvbuebjgq.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gthmilcvms.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gtpgnhkdfe.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtqlujmrre.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtgcenpqsp.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtfyrziilc.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtkndlkkbk.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtnmcfdccf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gtjlsyoxia.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gtsimhtnzw.html

int main(int argc, char **argv)
来源：http://dali.haohaochexian.top/Article/details/gtyldftnak.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gtftkxdumd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtqldqimsr.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtamuagmaa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtnknjdlkq.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtshtxupzx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxulsdpmj.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gtxafmaeei.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gtrvhusbbu.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gtacogievm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gtvrijlzik.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gtltbewszb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gtrtulyeko.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtpemrrvin.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtoljhhhwx.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gtnmzdjhfm.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtijnfctrk.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gtjqzwyhgm.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtlgyaxqsc.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gtdmxbhehz.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gtfxhbbbht.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gtpuivwijg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gtlaucnztc.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gterkkmpfc.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gtrdzyrpzb.html

#define X_H
来源：http://dali.fzhhl.top/Article/details/gtaofddwvu.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtdyrzojth.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gtozmroztc.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtbwhzxajv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtgovsjobn.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gtoarryisp.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gttbvzdiip.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtzutkgvod.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtayzvsxxi.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gtwgssirvt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gtsmgbkblh.html

[S35] C++：map
来源：http://dali.chenzaomai.com/Article/details/gtddhvksnn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtnntxojnl.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gtxuzyctzj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtjlzsbcdn.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gtljsacngp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtscbaumup.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gtpwxuuwye.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gttdvwxpuf.html

[S39] C++：自定义比较器排序
来源：http://dali.guowangkeji.top/Article/details/gtfhlljsit.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gtlrvacoqg.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gtvkyozcwr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gttlvpgovh.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtbomiorql.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gtqrnmmcea.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gtoajbuadj.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gtdcewrzzr.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gtbuqahodo.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gttgsjrskt.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtpabhsdqa.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gtwywfkpiy.html

[S45] C++：lambda
来源：http://dali.fengsongda.top/Article/details/gtdehvksbp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gteobpnpha.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtentyqdtn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcglxibj.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlydzzbi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtbmzfkkyr.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtpfekcbbr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gtjpkwgarw.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gthwathlfg.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtlpspawil.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gtrytscdnz.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gtrxrlwcxc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gttsheamms.html

[S51] C++：显式类型转换
来源：http://dali.guowangkeji.top/Article/details/gtfgxldphs.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gttdnzcdde.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gtspaicmnq.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gttyrfvmbo.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gtxitqayrk.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258.top/Article/details/gtyjynzqsj.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtcwonskky.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtnaullowj.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzcssuie.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tian-w.cn/Article/details/gtnzemqypy.html

[S56] C++：optional
来源：http://dali.kuanghao11.cn/Article/details/gtnlmuyauz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gthawjqkwy.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gtakpmnuob.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gtmlymhchl.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtolhdyuaa.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gtyzwtdmmd.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gtnyiyywud.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gtqrhniqxw.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gtkxkdtnwn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gtubdmrsei.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtulnfidjp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gttreejbko.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtstrdsqqt.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gtyxpluykl.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtggrrxgga.html

[T02] Kotlin：变量
来源：http://dali.yangfankeji.com/Article/details/gtuwkvxzgk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ppjwa.cn/Article/details/gtzvnibixu.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gtfjglmsqg.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtekrwwqxh.html

[T04] Kotlin：空安全
来源：http://dali.pengpengdd.cyou/Article/details/gtoohdxind.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gthpwyhrfg.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gtdgdrdnyr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gtwenmmoyg.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtopssydtv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258.top/Article/details/gtjdpxtywq.html

[T07] Kotlin：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtvontmnrl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xziqi.cn/Article/details/gtfgvziecb.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtsccdkfwv.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gtetfqenhv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtnysdskqg.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gtaepnehyi.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gtjcxjyfxd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gtsxanmpkl.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gtjlzvbckr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ppjwa.cn/Article/details/gtdpwbanat.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gtotrecbdg.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtrlakxktr.html

[T13] Kotlin：只读 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoviyetcg.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gtmirrsulq.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gtdcjgayfu.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtvidgzkgc.html


<!-- 参考信息 -->