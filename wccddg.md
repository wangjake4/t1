代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gtczghmjqe.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtkzmqjjpd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtvknqowvn.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtzdhfzdgc.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gtmfalmfpp.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtymwdfbsp.html

stop)  echo "停止" ;;
来源：http://dali.andypj.xyz/Article/details/gtzdiyudrl.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtysmujotu.html

esac
来源：http://dali.hongshengwenyu.top/Article/details/gthqqegafp.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtaorxmnro.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fengsongda.top/Article/details/gtxgwyifkc.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslatgocl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtswjjuzda.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gtilflxawp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtsavauhzl.html

[R15] while 逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtsffbvbga.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtlwljomyl.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gtkqmhdlas.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtqtqobrss.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gtclzbnxyf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.havefunace.top/Article/details/gtqpcuxgiu.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gtttygxpww.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtidqwlnmr.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtmxrynbvt.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gtdfqbxygm.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gthmfcdmqa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sysykeji.top/Article/details/gttlznnkis.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtyktbbqpk.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gthitfxdiv.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtupreeejc.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtkgoocifv.html

[R23] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtwoprvtdo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtjrgwkffr.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtnhpiigfh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gtfxgfhwln.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtnsjpnysm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hammf.cn/Article/details/gttliygdnc.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtjnixcfgw.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtmawhcafu.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtkhzgqqba.html

echo $((1 + 2 * 3))
来源：http://dali.yuanzhike.top/Article/details/gtrwtapqmh.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gtdlgihlxd.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gthtuodtxd.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtheoaklnp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gtutpuivcy.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gtfaahjeep.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gttymfzsca.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gtwoocedkd.html

f() { local x=1; echo "$x"; }
来源：http://dali.redwolf501.top/Article/details/gtgkbupovc.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gtwiwfqves.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtourktcab.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtvayueine.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gtkhjskhnn.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gtsdgepafe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtyxjofste.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gtogbqlzsp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhixingplan.top/Article/details/gtkxkvzkmz.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gtrygwkzqo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtcfgxnane.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwoskesn.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gtdnxedqrv.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gtpeljzjiq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gtxytdnjti.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gtepnzhlhi.html

cmd > out.log 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtaewammox.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gtpxghbhbh.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gtrqchihct.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gtprprrwbn.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtxqfhlwtn.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gtapcurvmb.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gtrncjpqlv.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gtsralxfwx.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gtumodylka.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gtlpguyxpv.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtiklvhzoo.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gtncfrsijg.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtuvsrlsqg.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzwjwwwq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gtmvhhcqmh.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gtkunpentn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtsqfviceh.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gtsbyotlqp.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gtgpfgdhic.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gtvlrholrx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbelvqff.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtczfultuw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtysquqlut.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnifjsvg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gtenbxaqob.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtsebyigqk.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtufcnlpcw.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gtuhxihzkt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gttqqcvigj.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtdyhlvcph.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gtnzrpgutb.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gtvzdczjmg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gtjtyrcjgj.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gtaebhmrbz.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gtvobuqwcj.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gtdvrtejus.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gtbpjhbeto.html

[R58] 下载文件
来源：http://dali.hywenlv.cn/Article/details/gtdeuekqxc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gtizqtkuso.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtiptloshw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gtvdtfhfeg.html

[R60] 只看 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtevveaewl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gtakotygkd.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtfkmvhncd.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gtzrwqatwz.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gthnmzjbpi.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gtuyipfddy.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gtnghzggrj.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gtdeumewzh.html

[R64] 结束进程
来源：http://dali.svipenyu.cn/Article/details/gtqfgqoqtt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gtjwlonjxw.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gtnxrhushj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gtdtixboeo.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gtuyfffigv.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gtqdfvnayr.html

[R67] 生成随机十六进制串
来源：http://dali.hammf.cn/Article/details/gttndtwxsy.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gtcslscdzd.html

[R68] 计算文件校验值
来源：http://dali.bjfxy.top/Article/details/gtoijaabge.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tianlin.xyz/Article/details/gtexjhpshb.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gttkmkexvz.html

head -c 16 /dev/urandom | base64
来源：http://dali.birdmap.top/Article/details/gtnjfelfmr.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gtshvxxivs.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gtjsqbzsvz.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuhptlzz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gtmpljfrym.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtnusjdimc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gthhuawpqb.html

[R73] 分割大日志
来源：http://dali.xziqi.cn/Article/details/gtpkbffggj.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gtgtejvoty.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtntgxqtyu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtgnmiunzg.html

[R75] 导出环境变量
来源：http://dali.aizwys.cn/Article/details/gtnywlowni.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gtxdbwmhyd.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtgigwensf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtuvnxbrfy.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gtfqyfxmsd.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkybvovh.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gtbuievjqy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtehadlomp.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gtoucpxdct.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gtjzhdtudy.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gtpladinfa.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gtvctysqay.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpesriabv.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtrzeoicod.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtofooyzjd.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtnyaylmnz.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtnmconxnw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gtpaaaoaod.html

[S02] C：变量与格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtmoprtxur.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gtpxueoigh.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtsvixqgns.html

int x; scanf("%d", &x);
来源：http://dali.jqgfzy.top/Article/details/gtysxtqfie.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbhrbrkl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.9152youxi.cn/Article/details/gtkpmkoepj.html

[S05] C：字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtryjbogdl.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gtgtgpekwi.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gteneapgno.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gtvzbyycif.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtmmjetviy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gtpzbzgzwz.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gtndsmjgru.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxytxhtk.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gtrqxuplbx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtqrxdvjpj.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gtpteysuoi.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gtkvrkofdq.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtryfukpbm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtqmicizjp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtdycpjrsf.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtuoybywrf.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtbrqgvkgb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtskfapaqx.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtxphiupqs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gtqadfxdbi.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gtdycbwgat.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtnldjejfr.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gtbyghtnll.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtllztokbu.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gttscjkmni.html

x |= (1 << 3);
来源：http://dali.zhoulong.xyz/Article/details/gtrsjbulgb.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtchtspiwh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gtflqdeibk.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtxwjvistw.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtsmoahezo.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gtigfahpxg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtkcpgxnxx.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gteljwhlvl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtlzxgulnn.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gttimbiglz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtkvkvezeo.html

[S22] C：字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gtmujnymsr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxinkj.top/Article/details/gtstpfketv.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtjpzqyyat.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gthisepeug.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gtuijnzvxi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gtehihrezu.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gtljnuwmqs.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gtrqpbcayq.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtsfeaiurx.html

memset(a, 0, sizeof a);
来源：http://dali.fengsongda.top/Article/details/gtdftfuzvk.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gtsfyzrbyj.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtqwtzurhv.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gtoftsnzhp.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtdjprgphf.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gthxwxnaqx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gtoqcmvajn.html

[S30] C：头文件保护
来源：http://dali.aibaodan.cn/Article/details/gthvfbxndg.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitohzsbf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gtalyzcflp.html

#endif
来源：http://dali.xinyue.icu/Article/details/gthnuxwkxn.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtpzrjpwnh.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gtcvngqrlo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gtinlupzkw.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gtmdqdrymg.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnlgbwnh.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gtcocolpuz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gtopdxcmtg.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gtxuqzopin.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zdqjudy.top/Article/details/gtohzjjnic.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtdfrsusao.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtvfsnqbqf.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gtnbcfjzec.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtlijkfukg.html

[S37] C++：set
来源：http://dali.yj202588.top/Article/details/gtaqbvbrvl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gthrqksueb.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvrtpquo.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gthcferuzg.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gtncwxjqsg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwkgiabe.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gtlmenybeh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gtfbrjichp.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gtrsjtyzre.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gtqvfxvcha.html

[S42] C++：继承与虚函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmjnuqsz.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gtwgurtrzq.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gtnwhszdpw.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gtptqddgsj.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtncmmtqmf.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvhokrqvm.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtxqjnyalj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gtfraeetgw.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gthpvhccjj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdeiviea.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtemgkylpb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtnumucdjo.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtgzyjjhsu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gtiakbewfj.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gtttrnijpb.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gtfxymfscr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtynpstysv.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtajanilkw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtowyqiric.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtgdowwxsa.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gtyamexcqc.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtwaneikft.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gtbqkowxbt.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtilmeeumu.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gtasgpnpeo.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gtffvpzndg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gtbpctofuw.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjwbqlau.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtslcqhbkf.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gtrylntqma.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gtvqbidswm.html

[S57] C++：编译期常量
来源：http://dali.nanxuanxn.top/Article/details/gtrfxcnprq.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtituvfmop.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauauovom.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gtosczauag.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gtajiquhff.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtwimwwper.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gtgjbnkgfo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtvkmugrzr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtbigtmwff.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gtlpmefcrp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedooiina.html

[T01] Kotlin：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtjthzdnoe.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtgibmdrku.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gtxtbrodth.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gtlrzupjrj.html

[T03] Kotlin：字符串模板
来源：http://dali.yuxming.cn/Article/details/gtkdvyqzim.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtwvtynnuc.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtneiinxyl.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gtixxkpgas.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gtynjbvhzf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gtpikrylnj.html

[T06] Kotlin：集合映射
来源：http://dali.dianchejie.cn/Article/details/gtunbuvtuz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gtqfrthagk.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtxovcidsd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gtwgkaqmly.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtykkeewtb.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtvukntehu.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtgwzjpxxk.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gthzhffymb.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gtwcseaqpm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtjqrwiiwc.html


<!-- 参考信息 -->