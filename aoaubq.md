代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gtkmxfykik.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdkfsrrc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtzcuduhvb.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gtipcuwave.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jyoumei.cn/Article/details/gttnxiqbcb.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gthdjuqcil.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtljfjlxls.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtiwppwnbk.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtrqdusbte.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gtsdmvnoyn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtayvphipb.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtmwefyhgj.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gtxnogrgjg.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtqekpiuwc.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gtigajxhpt.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemrsobxw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gtecucvian.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtzuoxfzwj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gtewomzrfn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gtvsrafymq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzaasqpa.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gtbfamsxrq.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gtopqgtuax.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gtpfjgpgfo.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gtxcdjorib.html

[R28] 浮点运算
来源：http://dali.meibo888.top/Article/details/gtmesjaoin.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gtlqpjveyo.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtejstkmes.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gthnbkswjc.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gtylfipeiq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gthbzjzemc.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gtxdztleyo.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdmzzpses.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gtzmldpitz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtrhyydbgb.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gtgaeowvaj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gtyzzpxqal.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtpqzyrrjg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtobhjtcdu.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gtbpofppqs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtfydhotkg.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtbgvibgci.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gtybuzjhgm.html

[R37] 把输出赋给变量
来源：http://dali.kuanghao11.cn/Article/details/gttjnbxbwg.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gtpaalpbjg.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gtdbgxaxlz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gtgxdxoqjw.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gtrcjsakkh.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gtvsgfhqno.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gteogdbxjy.html

echo "log" >> out.log
来源：http://dali.jqgfzy.top/Article/details/gtzrurkplm.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gtngumgbcu.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtrpwutxlo.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gtmtisioqd.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gtokietjtd.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtjvqnkswf.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtvaijepet.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gtyusmdsji.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmxrpqhy.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gtxwxjcwue.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gtnkpvgngz.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtlfbawoqm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtibitcggt.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gtkwecxixp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gtussdklxl.html

[R48] awk 取指定列
来源：http://dali.sysykeji.top/Article/details/gtqsmxknmo.html

awk '{print $1, $3}' a.txt
来源：http://dali.pycfn.com/Article/details/gtvbcwywwu.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gtmzewnouz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gtxdzefztb.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gtlojpkbpu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtteakript.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxiclhcs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.havefunace.top/Article/details/gtbsqbnlgb.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtvfdsayrq.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gtyldrjtuu.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtrninvayw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gtugnrrwhg.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gtopgbinzx.html

diff a.txt b.txt
来源：http://dali.hnxiangtu.top/Article/details/gtonddlhcz.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gtslmjfclv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gtbgrrnazc.html

[R56] 远程拷贝
来源：http://dali.zycfv.cn/Article/details/gtihgujmbk.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtbtyasetc.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gtudgufkpf.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gtajcrfsae.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gtfxdmsjkb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gtwslqtrli.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtenqldodg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwhefhcw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtsohpxlge.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yvedp.cn/Article/details/gttnjpqxmq.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gtwlmpzuru.html

df -h;  du -sh *
来源：http://dali.yangfankeji.com/Article/details/gturvdbkey.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gtedqfvoun.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtpyzwwaky.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtllskamtq.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtpxoxytdo.html

[R64] 结束进程
来源：http://dali.xinyue.icu/Article/details/gtezhyvmoc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gtyfpjqtam.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gtdtoosrmt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gtcgpvzfbc.html

[R66] 定时任务
来源：http://dali.hammf.cn/Article/details/gtdnbysauy.html

crontab -e;  crontab -l
来源：http://dali.yuanzhike.top/Article/details/gtgqqvmfcm.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gtbodiiqrb.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gtzyciapmx.html

[R68] 计算文件校验值
来源：http://dali.fzhhl.top/Article/details/gtiqdiyxbb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gtmmgdwlgk.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gtzoixhvts.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gtmymduvds.html

[R70] 时间戳与互转
来源：http://dali.sysykeji.top/Article/details/gttilztgid.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gtkqtmallb.html

[R71] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtgpgvdrbo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gtfgcrdimw.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gtmanapvvo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtbpgjycyn.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtmfnxacnw.html

split -l 1000 big.log part_
来源：http://dali.0kj1m.cn/Article/details/gtknbomaek.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtortdtqas.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fzhhl.top/Article/details/gtnvxkpiiy.html

[R75] 导出环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyfcvrzy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aizwys.cn/Article/details/gtwqrfwltx.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gtjormhwbb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtwwqzhfgl.html

[R77] 读取用户输入
来源：http://dali.bjfxy.top/Article/details/gtvumhjohw.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gtmocrgztq.html

[R78] 交互式菜单
来源：http://dali.jinghuilouyu.cn/Article/details/gtfakybjda.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gtkgsqdxnq.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gtglylmykr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfrmftyq.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gtpaiamqtj.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gtcrknjtqf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbrfxntlh.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gtbsmueibf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvpabpvwg.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinstsmgh.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gtqnekbmcy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.birdmap.top/Article/details/gtdetfzrdr.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtajsadcwi.html

int a = 10; printf("%d\n", a);
来源：http://dali.gzhubu.top/Article/details/gtikuwudie.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtsxfqmblq.html

int x; scanf("%d", &x);
来源：http://dali.aizwys.cn/Article/details/gtfmpnlahj.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtwmsvaxfl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtuqhfshpe.html

[S05] C：字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtxgwyqvmx.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gtgzdqkeyl.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gttjvhmwwc.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtfipwmgsz.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gtveatsrhb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gtyfefyksx.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gtqgqbgbqy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gtxodknahb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gtqoxwbtfh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.bjfxy.top/Article/details/gtruyreqle.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gtoiszndvf.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gtdizluhmk.html

[S11] C：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtuxvfgwzi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.feifeiyinyue.top/Article/details/gtngjwcazb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gthxxnsoim.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtlgvgfiql.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gtwrxsmzeh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhchujcy.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gtlyjesggb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gtvwzgubtm.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyhytzji.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gtskkrgscb.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gtplafwtut.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gtuujvakxx.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtddbuwx.html

x |= (1 << 3);
来源：http://dali.meibo888.top/Article/details/gtxzfvatpn.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gtvsxqeodm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtvqxwzohn.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtaphdekcj.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gtksfvibop.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gtcfqlykbl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtxokohcoj.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdunxiuhk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtdrojbjml.html

[S21] C：字符类别判断
来源：http://dali.jlsjyb.cn/Article/details/gtufoguggc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gtdyylbryr.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtdbsaovat.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gttmvaimtd.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gttftrdfal.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ybcxt.top/Article/details/gtnhdfumbf.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gtupyutecf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.9152youxi.cn/Article/details/gtliggxvjy.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gtcstrmwxv.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gtrafbbtik.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gtubyrujfe.html

memset(a, 0, sizeof a);
来源：http://dali.ybcxt.top/Article/details/gtlydnhvvo.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gtfpdeuqwl.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtkeyuybwc.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gtotomejzc.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gtcisnjmit.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gtbbatvwvq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gzhubu.top/Article/details/gtfunqjdkp.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtwemewurv.html

#ifndef X_H
来源：http://dali.cucudq.cn/Article/details/gtahozmdam.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gtgdmjkbth.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtgrzwdqzz.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtuldmginn.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gtlhbdgido.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gtapupdfmz.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gtgyeegcwt.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gtxzqmnmnh.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtjhttvarx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtwylodbix.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gtxukrlyos.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gtouksapaw.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gtumkmwdam.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtreaythff.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gtpunxruns.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtplcypskv.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gtgotobzjs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gtoifgbtkv.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gtxhhckcay.html

std::sort(v.begin(), v.end());
来源：http://dali.yueranfly.top/Article/details/gtffywksjw.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gteqczcyqd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gtiabwdxew.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtslbbndqn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sxryk.cn/Article/details/gtwmulhjok.html

[S41] C++：类与构造函数
来源：http://dali.yonumen.top/Article/details/gtvfeclpgq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gtbrvwllef.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gtdmnhgwpc.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gtojkhzkzd.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaadqdmcb.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gtmcesarxp.html

[S44] C++：引用传参
来源：http://dali.tanke756.top/Article/details/gtpekoguci.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtgagqjtjz.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtrzllzsad.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gtkypczqhw.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gtmoeislfv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtmkvqjlrz.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gtyeysmcwv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gtfchtpjsm.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtdxyjpqxg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daxiang520.top/Article/details/gtovwlwtns.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gtckwyxyfw.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtaksviytk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gtogqpltlb.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gtxswbtpwr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtbpqxstyj.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywuaifiw.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gtpmgzezgp.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gttjhpjngi.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gtijwwackv.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gtewmuzmyt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gtskjhkfpr.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gtyntiufgh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtmhbiskaj.html

[S55] C++：结构化绑定
来源：http://dali.yongpay.top/Article/details/gtbmglqdko.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtnmqappmm.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gttdzfofkj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gtgtrgaphh.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gttedcvtqd.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gtwjzvzotg.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gtuwvzwyab.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gtclngptoa.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtjbqejfnm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gtdcmgekbi.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gthgmlpnvi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gticertbov.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqtdjikcw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtzfnjsnpu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gttqlcttci.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gttzmwjzba.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtlnzotuct.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gtniljwkuk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtzvplemzq.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gtljvjimqz.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtdelwqusv.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gtnkqifutk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gtrulslndn.html

[T05] Kotlin：when 表达式
来源：http://dali.ehwqpu.com/Article/details/gtlmijnyxq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daxiang520.top/Article/details/gtovcfmdle.html

[T06] Kotlin：集合映射
来源：http://dali.ydzc1.top/Article/details/gtfqesrsnt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258888.top/Article/details/gtewypomll.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gtsgspornr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gtnphertvr.html

[T08] Kotlin：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrnkgewy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtnhmdjwsz.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gtammyzraj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gtzeczvaud.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gtjzstxbng.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gtonliubon.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gtdhirfztv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenjidiqi.icu/Article/details/gtcvekahct.html

[T12] Kotlin：解构声明
来源：http://dali.jiagoushi.top/Article/details/gtcssacycn.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzepoofcl.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gtzxmjkfmu.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gtedizicpe.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gtpzzckmdl.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtqvslcqtl.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtucngfptc.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gtaskruegg.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gtmsffaiwv.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtonwytgpe.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gtkstypmrn.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gtvaxayyke.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtdxnaejoi.html

"值: \(b)"
来源：http://dali.yonumen.top/Article/details/gtxrgyifml.html


<!-- 参考信息 -->