代发 wailian999

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gtxaukkhfc.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gttvousufp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtrhidqudo.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gtsrgiluzu.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gthuzbcvwr.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gtuzrbuuct.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtkklpzlhd.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gtsqjxozto.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gtjalxxhtr.html

[R08] 数值比较
来源：http://dali.hfpthk.cn/Article/details/gtyertavvk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtfyypukrv.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtemldbxwx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gtianwkwgr.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gtjdtiqpmq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gturtsmcej.html

[R11] case 多分支
来源：http://dali.zhongyouzk.top/Article/details/gtjsiglmco.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gtodhvvtdy.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtgjdsbkot.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtlllvdtot.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtjhwxnydp.html

esac
来源：http://dali.birdmap.top/Article/details/gtfxqsqnyo.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gtyreobzrx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.meibo888.top/Article/details/gtrfambbgi.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtvioqkgie.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtryamvdfi.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gtbwltzzoa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gthumqjvcp.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtbglyffix.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gtgfytnkbe.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtjmurhvmw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtxnuxfkua.html

[R17] 数组定义与取值
来源：http://dali.yj20258888.top/Article/details/gtajghgceb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gtzubrdrii.html

[R18] 遍历数组
来源：http://dali.sxryk.cn/Article/details/gttfzbyyub.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtaazjihma.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gtlmyzxqbn.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtdzdpmvuo.html

[R20] 关联数组（字典）
来源：http://dali.yj20258888.top/Article/details/gtlprcnjpc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.bjfxy.top/Article/details/gtjhmbqmtt.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtwmhvfbox.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtwahrxnsu.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gtebdofglc.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gtzhbdalrm.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtjdeguemc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gtlkpzirbo.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtjwyqmubg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gthbsauvfr.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gthyzgwgar.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtqunfejgp.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gthuyipcrc.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gttqlmpzyw.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gteqjwplvy.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilobxyhp.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gtlenqegqq.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtbmugzliq.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gtjcigxtqf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjqgwmmd.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gtllsyqsxv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gtwuxyqizt.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gtctttoxku.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gtwsqzoutw.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtpimyjccm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtulyqkjjh.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gtaqbzqdnr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gtjivteanp.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gturonpagp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gthaiekpyb.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtgoiwgtkn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sysykeji.top/Article/details/gtupcuqvqe.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gtvhiaptoa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gtuxbzxxlq.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gturmuvymt.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gthyeheojy.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gttzzhyskv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gtgjxixqnu.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gtcomgwtds.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtxgzkrinc.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtnynsxtlt.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gtxkgenfdj.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtrqyxnfid.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gttrxrijhm.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gtbhgtfiyh.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtceygccox.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gtbfelqfbh.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtgvpkvdty.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gtdsctirvp.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtmhakuwic.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gtpuietksp.html

find . -name "*.tmp" -delete
来源：http://dali.nanxinkj.top/Article/details/gtuvjcskpm.html

[R46] 递归替换文件内容
来源：http://dali.chenjidiqi.icu/Article/details/gtmvbieezg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gtkilxxndo.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gtiqnnnjri.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtslwehfbr.html

[R48] awk 取指定列
来源：http://dali.ehwqpu.com/Article/details/gtzcicmraj.html

awk '{print $1, $3}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtyjfrptat.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtjnggbmcl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gtonqlmkdc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gtxllroqqp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtibhpwjuj.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtccadplru.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gtprmwnnpi.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gtspvfbprj.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtzlymjrqw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gtowsabycd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gtoutmcqzk.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gtxlpcqwgz.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtmqcclaaj.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gtczfwratb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gtiykflbja.html

[R56] 远程拷贝
来源：http://dali.daria6918.cn/Article/details/gteftgxodi.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gtmrxvqxmx.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gtdtigibjz.html

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gtcdngyvae.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gtnqtsxrrf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yangfankeji.com/Article/details/gtnckgbpln.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtvrdbwfsj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoajlgtxa.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtfznrcjwz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gtalmmbumb.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gterhsrmbc.html

df -h;  du -sh *
来源：http://dali.sufxvd.cn/Article/details/gtklzcwcmt.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gthncvvuyg.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtcyzwwczl.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gtoenltiui.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gtqzswgdqy.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gtrgytrmhj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gtvglreffl.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtqrrihake.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtypyeftwx.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gtfzraoidf.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gtnzjvwilm.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gtfmdmjncm.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtriycgtid.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gtpjckxtzi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtwpbeetdz.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gtkjpvorwt.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnscvfvbo.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtegcfbhwp.html

date +%s;  date -d @1700000000
来源：http://dali.jiagoushi.top/Article/details/gtokxjvoqf.html

[R71] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtmyfkgwgq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gthphfsybm.html

[R72] 等待端口就绪
来源：http://dali.svipenyu.cn/Article/details/gtdhhvcivc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtnwhkteed.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gtyslporvt.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gtaybdfzui.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtmzvgcinm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtrglzrjaj.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gtrekdlhjv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtystsmaqp.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtnuqntgln.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtwdfomloa.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gtmucbxdod.html

read -rp "请输入: " ans
来源：http://dali.dashuyun.cn/Article/details/gtptnalhef.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmnpidxm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gtfjhsddcc.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtjrpkppwr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtlqqweyiu.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gttmtsutzn.html

time ./run.sh
来源：http://dali.shuidangran.top/Article/details/gtigedwuxx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyzsevstc.html

S. C / C++ 专题
来源：http://dali.tianlin.xyz/Article/details/gtavacndhp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdkkygzqq.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtmrjkrxwk.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gtfxpyvkgh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gtaltifcml.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtdmftiizr.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gtqotbjdpi.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gtztdpcqtn.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gtyoizmpqg.html

[S04] C：字符串复制
来源：http://dali.aizwys.cn/Article/details/gtjrghcwfc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtzeifwobf.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gtognmqyzk.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gtukytqxnr.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtttukyzzs.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gtdherhujl.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gtqgajvelg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gtvtfgljkc.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gttyefcfaw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shuidangran.top/Article/details/gtvtfyxqtk.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gtyyqeelua.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtuewqqolm.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtlxwpfzda.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gtgszqothc.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtzvwvumhf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gtpdxpeemk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gtivfowofz.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtdvkzzwgo.html

[S12] C：写文件
来源：http://dali.sysykeji.top/Article/details/gtabcuzdei.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtpxisxomy.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gthynijnxn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtbstjckpu.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtvbmakevd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gtbreulhkt.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtsrwvaeky.html

(double) a / b
来源：http://dali.cashguo.top/Article/details/gtsywckewi.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gtfqewtkcj.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gtpkqphjbt.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtqdkbplwj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gthnflussp.html

[S18] C：命令行参数
来源：http://dali.zycfv.cn/Article/details/gtgarucpoc.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtkjecrjyy.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gtnvskvigs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtkxpooslx.html

[S20] C：二分查找
来源：http://dali.guannengcc.top/Article/details/gtzvckjyfp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtonqfasou.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gtywyfhfnh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gtryyopmbq.html

[S22] C：字符串转数字
来源：http://dali.cashguo.top/Article/details/gtdqvajsdi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gtvgquyeig.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gtuffjgoqm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gtdfwiqbcp.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtvoeyvfon.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gtxauwyhyw.html

[S25] C：内存拷贝
来源：http://dali.xylfe.cn/Article/details/gtchbkwguk.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gttxiuhxon.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gtlqskaepr.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gtwpdepsxt.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftjdnnjr.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtlvfoaqjo.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtuxnfemmt.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtknzhefdx.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gtwjspmvem.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gtbciqfynt.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtblbqnmcy.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gtoowhfcso.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtxjkpkhqr.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtuwfmfowp.html

[S31] C++：Hello World
来源：http://dali.xuanzx.com/Article/details/gtnygpqufs.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gtvvprqarn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuanzx.com/Article/details/gtxiztulzw.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmmdmesy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gtjglaeiqy.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gtxofpoffr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gtrjwdnazm.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gtkzbsnzqw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gtlejcvucw.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gtcbzbdtgy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtbdyteunx.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtgskdrsay.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtabiycalo.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gtvfultcde.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtidgmogjq.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gtsauljxlz.html

std::sort(v.begin(), v.end());
来源：http://dali.birdmap.top/Article/details/gtujofwcej.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gthmjzxnhx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gtmwbhdkrp.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gtkhuwusre.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtaooojctr.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxasrlxxi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtmaudftij.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gtmndetimg.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gtbpyvvubo.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gtyddecebs.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtedvfitjz.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtfmsybolp.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gtlctfbhxq.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gttbvixbiw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gtcypuvphi.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtzaxlayve.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gtontdynxc.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwyvemki.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gtelzczebr.html

[S48] C++：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtyzwarwqz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtbtwpfixw.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtvusdglpk.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtxhpwbfmc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gtlwezakqs.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gtohwkucye.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtkbplljbo.html

[S51] C++：显式类型转换
来源：http://dali.fengsongda.top/Article/details/gtnxtoxjkm.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gtpkmmztaf.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gtvrucfvaa.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtqyblfcfo.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gtgwzblpys.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gthmxwcxsh.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gtjqttxrcg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtoavwrari.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gtdrcdejlt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gtauhvefnh.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gtcdwhjdih.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxsrabbsg.html

[S57] C++：编译期常量
来源：http://dali.0kj1m.cn/Article/details/gtxvqcpqdm.html

constexpr int N = 10;
来源：http://dali.cqqwz.cn/Article/details/gtxdljuroq.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gtcaigwylh.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtsmeidakz.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gtwgyepfmx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtwhptyzpb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtwknipcom.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtdlclgszm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtumyfcdfn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gtywyaratj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtntbyvijx.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gtrdtplzuf.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtyjaglrra.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gtjbmewdkz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtopeforis.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtmoniinwh.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtcxjabgbc.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gtlsusjalg.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gtpnlxtuae.html


<!-- 参考信息 -->