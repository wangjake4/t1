代发 wailian999

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshlayvka.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gtdptnshcn.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gtcvmgggem.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gthlbrcbow.html

esac
来源：http://dali.cheryme.top/Article/details/gttfxujlju.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gtyhybvige.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gtvvyksrii.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtcuvvjcng.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gttstbssml.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gtorseiogr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtjezzzaot.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtogbinasz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtrvnajppz.html

[R16] until 等待条件
来源：http://dali.cdnleiting.top/Article/details/gtsguioraa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtfdqbdqmw.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gthinpjsjj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gtefnfesad.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gttucvglue.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtcobeabom.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtzsgmlfxo.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gtzskgymlz.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtfrzissbk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtmbwjawpo.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gthttiuffz.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gtxzsalxvn.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtbkbdovwy.html

echo "${s:0:5}"
来源：http://dali.yj20258888.top/Article/details/gtihxfcntd.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgzsjerz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtlrwnitbt.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtrjqzknef.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gteuxmujtt.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gtmsnclojg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gtejcyjsol.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gtruqqnedg.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtckiajbnt.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtmasuofpc.html

echo $((1 + 2 * 3))
来源：http://dali.nanxuanxn.top/Article/details/gtyaalnkor.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gtbiuwbwzi.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtsisjfohc.html

[R29] 定义函数
来源：http://dali.daxiang520.top/Article/details/gtjnvdfzff.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtcyzlviby.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtqaesypmc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yangfankeji.com/Article/details/gtumidezyk.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gttkcrwqpc.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyfnsdnw.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gtxhwednlk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gthfniskgy.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtrvyjzdap.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangshuangyany.cn/Article/details/gttnkqjtxa.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gtfniaswok.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtnlzchifs.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gtuvwwmjdp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gtjwgbulbh.html

[R36] 并发执行多个任务
来源：http://dali.hfpthk.cn/Article/details/gtouuarmpb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gtjwuwzerl.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtlirifdol.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gtytygyfzn.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gtoogxljxi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gtqkomajte.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtqwdohgqo.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgzgyeif.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gtehhuvhdp.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdixzfqeu.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gteqfbriyu.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtdedaigmf.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcnisyws.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gtnkvsxqso.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gtptxbtraa.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gtftkuxduk.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gtfmuhwbgl.html

find . -mtime -7 -type f
来源：http://dali.sufxvd.cn/Article/details/gthpfbzkwn.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gtecedkyma.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gthuxqjhmb.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gtbogoksyn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gtzdxxqhgy.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gtngwpjtwv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtlikdvnud.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gtnieisiip.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtvipovmdu.html

[R49] awk 带条件
来源：http://dali.aibaodan.cn/Article/details/gtmhenahrp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gtnhuqoqkn.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gtsgqzpwre.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtdyeaaekj.html

[R51] 排序去重取前几
来源：http://dali.pycfn.com/Article/details/gtparmeuld.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gtpkpnvjks.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gtgpclpxmz.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtyxbjitne.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtciodavjm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqyonqga.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtzhpujniw.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gtuvckvolj.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gtgshukvfd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gtqocjrmzk.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gthmvcaryh.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtcxngcauv.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gteuejabzp.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtwqhpdzmh.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gtnmomrdtu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtcevtclix.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gthbqjkgma.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gttncogrip.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtmzzcoinj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gtpariifhn.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtbboncvum.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gtwkdtzbvq.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gtgtlkvlhk.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtnoiopbca.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gtkfpozaro.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtaaehspvw.html

[R64] 结束进程
来源：http://dali.jyoumei.cn/Article/details/gtmvgoaedv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtoqfioeik.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gtaxhjghcb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gtavqfkqsz.html

[R66] 定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtzdvoupjc.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gtcyrbbhxy.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtekuqvops.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gtfopllfaf.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gtslmiienl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gtoxqjgovi.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gtgfrnpwed.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gtoktknrmn.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gtsevxbybz.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtedjlajlf.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gthobkhcde.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gtoucuxesm.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtsxdempjx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtwjqmhzpq.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gtleydowjw.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gtzjmoijnw.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gtfvcdofdi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtckbbrpgx.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gtggcdowtl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gthluzipfa.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gtndctfoia.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtyzdcnofm.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtftthufrt.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gthffkjcck.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gtpyxykari.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtmokzeiiz.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtmeaajzeb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtnnbocphb.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gtlawalxka.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtuygthdmn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgmjqqwtf.html

S. C / C++ 专题
来源：http://dali.hammf.cn/Article/details/gtbitksnjp.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtexjzsnkz.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtmuugrjch.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtxsfcklyb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtrmicanjv.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtgvbowesx.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gtzhbsgthl.html

[S03] C：读入整数
来源：http://dali.yj202588.top/Article/details/gthwiniacj.html

int x; scanf("%d", &x);
来源：http://dali.shuidangran.top/Article/details/gtgnebagzp.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtksihxuse.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbuunrlc.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtmiktunwy.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtamlkvsru.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtlvdvaqrw.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpzfvtgc.html

[S07] C：数组遍历求和
来源：http://dali.yueranfly.top/Article/details/gtpnarfesl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtktzdxwkt.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gtlpglrhzv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gteykpsxyt.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gtfnyhbdwl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shuidangran.top/Article/details/gtpkpokqvm.html

[S10] C：指针与解引用
来源：http://dali.snrcjt.cn/Article/details/gtsoeffmci.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gtyttvbodx.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtwuddavdf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sysykeji.top/Article/details/gtyblrxusj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtbojdyxhe.html

fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gtdwycgone.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gttrrmvgqx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtumlsbzud.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gtzotjwpke.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gtmxistket.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtahypovxh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gtagxgpsps.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtjtwfyqax.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gtusncqlmo.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gtbzggdwkl.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtzxkqpbjv.html

[S17] C：安全拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtkfjxozsk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtfkyoofxg.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtfbiwlcbc.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gtgioczxyc.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtxsqjfsjk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtguacyjit.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gtsbpskiuz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtlydtpeqa.html

[S21] C：字符类别判断
来源：http://dali.hywenlv.cn/Article/details/gtsbkudtsk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gthyakuzoz.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtvsbvqtvf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gtcfsqegpw.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gthhvkexhu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gtgbbndzdq.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gtpafihruv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gtayvdosfe.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxdoavls.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtguuxnmwn.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gthpmubbnc.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gtkvruzcha.html

[S27] C：定义常量
来源：http://dali.fzhhl.top/Article/details/gttonwgpnx.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtfbhrwnsa.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gtzgdywwom.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gtaejobytq.html

[S29] C：变参函数
来源：http://dali.jinqigfzy.top/Article/details/gtaastrzef.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gtdfpqutwn.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtxgbxcbgg.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtzwiksmfv.html

#define X_H
来源：http://dali.sysykeji.top/Article/details/gtpcsqkzef.html

#endif
来源：http://dali.havefunace.top/Article/details/gtdcketlrl.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtatytcfcp.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gtkljgnhgp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gttqlsxbha.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gtvfgofkku.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gtuzkweurn.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gtnxpwcwjc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtgwmaowuj.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqbbsowo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gtcrfnnkrv.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gtxtmblqkl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtuhaqzngv.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtmxwqnblx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtsthforyz.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gtltoeahli.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gtvvafljfk.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gtpedafttm.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrospywc.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gtkfgwtzfu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsljxrfre.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gtopojmobo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtphrdxfxb.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtevcxtmlg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hammf.cn/Article/details/gtehggdlpy.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gtcvzwlwxp.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gtkfizhhgz.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gtjfufbneo.html

auto p = std::make_unique<int>(5);
来源：http://dali.guannengcc.top/Article/details/gtzkxzcsxz.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtmzaallcs.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gtgmjwnjnq.html

[S45] C++：lambda
来源：http://dali.sufxvd.cn/Article/details/gtcjiebrpi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtiimapfxv.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtkwjllvdi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtshzmrvsy.html

[S47] C++：结构化绑定遍历
来源：http://dali.fengsongda.top/Article/details/gthhxyptbm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gtsoiyfjjg.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtkhhvciah.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.havefunace.top/Article/details/gtivdkwfyj.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gttouxxjzf.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtthmwedvr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shuidangran.top/Article/details/gtfcsinwis.html

[S50] C++：格式化数字
来源：http://dali.xziqi.cn/Article/details/gthnvzjbkl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtmpuqhbsg.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gttxkaajgv.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gtvtgkufde.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gtnhzefjjy.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gtiwifxioj.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gtzxwoqvwt.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gtewicwfdx.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gthcszukpd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbashbye.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gtfvkvfhqd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtgozhkquk.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gtxwjjfkkl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrzfwigm.html

[S57] C++：编译期常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhsjttda.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gtlgrfkrvm.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtedjtqchb.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gttukhehwa.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtgqdirpgg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gttdflyfhu.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gtdxxugegd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shuidangran.top/Article/details/gtyinkaqlh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtdiazfqvb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gtnxaqxlau.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwrihqeng.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtrxwahnuf.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtoonfhode.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gthkwdxtey.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ppjwa.cn/Article/details/gtheyyxsre.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gtlhlndgwc.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtzvopljkp.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gtutfsfrcj.html

val n: String? = null;  n?.length
来源：http://dali.yvedp.cn/Article/details/gtfnbzynkc.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gtgscaazdl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ybcxt.top/Article/details/gtozcliinx.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtkzszcfra.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangdashe.top/Article/details/gtrtrzbzor.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtoifoyyzi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gtykkymtfo.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gtbrpwhkxc.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtzzbdkmex.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gtgdqkltbf.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtecfwzlgk.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtduguzuwo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gtsnkmnvyp.html

[T11] Kotlin：协程
来源：http://dali.shzxlz.cn/Article/details/gtwovrboww.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gtgrrrumjp.html

[T12] Kotlin：解构声明
来源：http://dali.fzhhl.top/Article/details/gtxtwajpey.html

val (a, b) = Pair(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtelricotz.html


<!-- 参考信息 -->