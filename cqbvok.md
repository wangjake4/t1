代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gtxfgslnkb.html

[R10] 正则匹配
来源：http://dali.nanxuanxn.top/Article/details/gtdaravgft.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gtxbmmiytl.html

[R11] case 多分支
来源：http://dali.dianchejie.cn/Article/details/gtyaaibfjk.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gtcyylvwwa.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gtaescnhpg.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gtfynszwgv.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtgvgizxdg.html

esac
来源：http://dali.pycfn.com/Article/details/gtqzhymcxq.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtophmeqfz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigfzy.top/Article/details/gtoscdqlwy.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gtaevayawj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnilcdwv.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gthfjhnaqr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gthtfpfsqp.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtfebfzxzo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gtejetumse.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtrgdniqkc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtlobhsnbr.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gtuipozyst.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yongpay.top/Article/details/gtpkxxoqsr.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gtsucbqxny.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gteuzetygu.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtypcuiixr.html

echo "${#arr[@]}"
来源：http://dali.snrcjt.cn/Article/details/gtnlghzpme.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gtdybjlrvd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gtupoacoxu.html

[R21] 字符串长度
来源：http://dali.yueranfly.top/Article/details/gtbvxalodt.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gttignolxm.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtuqdihpkr.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gtvgjmkzfs.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtzcbzasxy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtsvttsjgj.html

[R24] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtfuavtked.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gtxbbyryez.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtlvnapher.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gtjgqvjtov.html

[R26] 命令替换
来源：http://dali.aibaodan.cn/Article/details/gtnwzdpnkh.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtsqrtgmhb.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzsupchz.html

echo $((1 + 2 * 3))
来源：http://dali.smart0.xyz/Article/details/gtoszcewfd.html

[R28] 浮点运算
来源：http://dali.hammf.cn/Article/details/gtvlryvvfs.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtekwninoy.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtohbjwtgw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gtajnscrfa.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gtbiyggauo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtchgkdscp.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gtoyxkokin.html

f() { local x=1; echo "$x"; }
来源：http://dali.shuidangran.top/Article/details/gthdewdbpc.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpufdswie.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtjriwewdt.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gtsuacymor.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gtmgmfijsr.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gtdcirclwc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtzbhqrqpa.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtamhsvgif.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fengsongda.top/Article/details/gtovktwvhm.html

[R36] 并发执行多个任务
来源：http://dali.c1oappe.top/Article/details/gtduuvoins.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gtkuakgbna.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtrwkzsuzb.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gtdozivxcx.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gtzqfyfdki.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cashguo.top/Article/details/gtpiajbdpf.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtkstchxne.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtniuzjcnp.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gtbpcmvigd.html

echo "log" >> out.log
来源：http://dali.dashuyun.cn/Article/details/gtiifjevvt.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtsiggeuhm.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtumdbaxlz.html

[R42] 输入重定向
来源：http://dali.jqgufenzy.top/Article/details/gtjqxbssap.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gtncmlalix.html

[R43] 按名字查找文件
来源：http://dali.gotoacloud.top/Article/details/gtileovqyg.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtytcxmzba.html

[R44] 按修改时间查找
来源：http://dali.ybcxt.top/Article/details/gtsfyqswcb.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gtagjvexnc.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gtxzkcglib.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlrzmueg.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtmknzoohs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tian-w.cn/Article/details/gtxskhgyuh.html

[R47] sed 单行替换
来源：http://dali.0kj1m.cn/Article/details/gtoqxismdy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gtakpuyomk.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gtpcsoidyg.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtocfafazy.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gtelbpjetx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtwxobvmcg.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gtjclzranq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtaapvsgpa.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gtmlugconw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gtydrofguz.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gtrwelsado.html

wc -l a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxccydsw.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtqjhnzdut.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gtgyleolns.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtuixxvlzr.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtcgrzqpwp.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gtxxgwbsba.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gtgszzallf.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gtfprgmshn.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gtxufongjb.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gteddkwdae.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gtjlwapnzy.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gtvcmuefhg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gticrqursh.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gttaofoena.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jyoumei.cn/Article/details/gtqozdbhhs.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtpsnnxpyr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgilajpei.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gtrknwvafp.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gtatpwzlve.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtvzjrifkm.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gtwzprqsby.html

[R63] 内存与进程
来源：http://dali.pengpengdd.cyou/Article/details/gtpepmjtnn.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gtxnxamgyj.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtemlvijjv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtjgjpmkks.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpcpxqsv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gtlrctokpk.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gtifacndah.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtecpgwzxp.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gtmtmugaxm.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gtbrzjkvfr.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gtpywmwbrn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqllhjvoi.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtxkounoqs.html

head -c 16 /dev/urandom | base64
来源：http://dali.nwbrower.top/Article/details/gtocwkeshr.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtevhpdvqu.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gtqnetgdvx.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtbfyqwcon.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gtkdbuoyjg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gthvhrpweh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtezdrjutc.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gtmemwbznr.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtmqtprhmh.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gtuvtnciom.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gtzqcmcsvw.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtfmadtjva.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gogol.net.cn/Article/details/gtrchwmsra.html

[R76] 使用临时文件
来源：http://dali.cdnleiting.top/Article/details/gtcwxcfyfm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtkcjzrkgx.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gtyqhafywu.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gtpjmckqgb.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gtbnxdetgh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gtmvesaohw.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gtyfbwtklr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtlkoyczdg.html

[R80] 查看脚本执行耗时
来源：http://dali.cashguo.top/Article/details/gtwwvxqqgu.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gttiqpzjux.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtirqwazdt.html

S. C / C++ 专题
来源：http://dali.chenzaomai.com/Article/details/gtmtrkwhex.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthcahpiye.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gtuqcbaehg.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gtbcvzlypv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gtxvmsjbqi.html

[S02] C：变量与格式化输出
来源：http://dali.yueranfly.top/Article/details/gtwlmfczvo.html

int a = 10; printf("%d\n", a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymhqkuub.html

[S03] C：读入整数
来源：http://dali.zycfv.cn/Article/details/gtdogvoerf.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gtamwphurs.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyktdrjj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttiafriz.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gtcgqstuwh.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gtjobsubyq.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtcxjlnlqr.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtuvkkdlyd.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gtitntqdpb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gtahodafof.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gtdfvvsden.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xinyue.icu/Article/details/gtgcmmmokx.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gtwniabtdw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gtdyiuwjtn.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtftglnakh.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gtsjydrwlk.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtkivumhnw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ivvv.top/Article/details/gtcgaggbwi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtuuarhoza.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtstwhhubs.html

[S12] C：写文件
来源：http://dali.shuidangran.top/Article/details/gtclgapiot.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtdosveuwo.html

[S13] C：宏定义
来源：http://dali.cashguo.top/Article/details/gtdpsggsqv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gtgpsuvogp.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gtlqbmkute.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gtowygoaku.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gtdlbzrkzl.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtfmzswazi.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gtuzodeeaq.html

x |= (1 << 3);
来源：http://dali.cucudq.cn/Article/details/gtmdjngoxi.html

[S17] C：安全拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtuwlgfzzi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gtesweywru.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllidqsvq.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gtevvkgowo.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gtfjihqbed.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtptznxcut.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gtvyniehbh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtjkgkehjk.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgrcgiyj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtkpqogawq.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtxgwobjul.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gtxltiuuxh.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gtsmlbsdnx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pycfn.com/Article/details/gtresdcods.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gtwfmksjyy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmvfajvp.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gtvsmwmxie.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gtvbffgsux.html

[S26] C：内存清零
来源：http://dali.shzxlz.cn/Article/details/gtmbbdoiud.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gtgqyaypcx.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gtivnqtpep.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtsjihnilo.html

[S28] C：静态变量
来源：http://dali.jiagoushi.top/Article/details/gtplowbser.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gtdogpewny.html

[S29] C：变参函数
来源：http://dali.yj20258888.top/Article/details/gtpfkvxxsa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gtjkcfogxn.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtqljtbblv.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gthjegynfz.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gtbskgiefa.html

#endif
来源：http://dali.0kj1m.cn/Article/details/gtdipkzfgz.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtgovgjivj.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gtgjgpbryi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtswvwfkhq.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gtghgckaue.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gtolvqzbvz.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gtlaqbqfnf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfblrapvf.html

[S34] C++：遍历 vector
来源：http://dali.zhixingplan.top/Article/details/gtpyyiywpi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj202588.top/Article/details/gtzifpgxox.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gtrukqdktm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtuwodidmi.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtwswxszqj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtprnwanvg.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gtntdxovna.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258.top/Article/details/gtbligbgdx.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gtrrzmqyho.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtyfzkghra.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gtzzyuqcla.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gttmwmovhd.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtkpdywkcj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gtnpxkwtjm.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gtbmlbaixn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj202588.top/Article/details/gtcetrhlfb.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gtoypyvyib.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmasvfpx.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gtlqshwudn.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gttjoyvpxj.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtkybojejk.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gthdahvyei.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtralujsdb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gtkoyurpui.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gtyqvymvum.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gtxqjyywdo.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtqlpbeoau.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gtpwklnnmz.html

[S48] C++：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmeuzcmie.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtpnuhwjub.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtxizfknkk.html

[S49] C++：写文件
来源：http://dali.yuanzhike.top/Article/details/gtvbucbrnr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtrgmzymfr.html

[S50] C++：格式化数字
来源：http://dali.jqgufenzy.top/Article/details/gtadnkgfol.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gttgbcperj.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtoqbgbzxr.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gtiupdvtuf.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gtdpsdbmvq.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gtwnlkawmq.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gtvkyjekvb.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gtjrfkhyiu.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtldxvwdmn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkxdkpcb.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gtspzptalo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtxwvrkxfk.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkoosqten.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtclxnfsih.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gtawoxaomi.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtjfjhqfme.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gtspsgpxqv.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtwdgxeizl.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gtepavkpgv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuxming.cn/Article/details/gtlosvfgzd.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtavxpvpan.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtxosddjly.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxmbfycmt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gtvvnshnxv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqhlmjehj.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtyvfaprua.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtjechtjtv.html

[T02] Kotlin：变量
来源：http://dali.yj202588.top/Article/details/gtxyrnbcey.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gtcemdwfup.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gtyalwlzwz.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtxbtiaakf.html

[T04] Kotlin：空安全
来源：http://dali.hnxiangtu.top/Article/details/gtplzxphtw.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gtcsbyylqw.html

[T05] Kotlin：when 表达式
来源：http://dali.hnxiangtu.top/Article/details/gtlllrcbrg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtaqqwbbbz.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsejfwfwc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtoktsvnzh.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtfevivjlo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gtemcftwtx.html

[T08] Kotlin：数据类
来源：http://dali.hywenlv.cn/Article/details/gtbzmaqbbf.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtwkthyezy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtzjxpgmrx.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gteuuuetzy.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtsvaiymbu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zycfv.cn/Article/details/gtbplxxxym.html


<!-- 参考信息 -->