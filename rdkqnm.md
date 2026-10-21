代发 wailian999

name="${1:-default}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgwfjyxp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gttdftoruq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtwstrolpq.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gtyapfvjif.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gtnqkkynjp.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gtnwwypivn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gtxivjembh.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gthmbtmrxf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sufxvd.cn/Article/details/gtqkhgnxyo.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gtayrpnjzw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shuidangran.top/Article/details/gtwjxsircp.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gtcuimzngf.html

case "$1" in
来源：http://dali.yuxming.cn/Article/details/gtzibxefkg.html

start) echo "启动" ;;
来源：http://dali.yuanzhike.top/Article/details/gtolcqpjnh.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gtcqkddycq.html

*)     echo "未知命令" ;;
来源：http://dali.dashuyun.cn/Article/details/gtfkwqrdnp.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakbfehdc.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gtymnxchxz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.c1oappe.top/Article/details/gtalogllph.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtikhytyys.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtauoanrrj.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gttgnarywn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtvbpogwdo.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgebypdy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yonumen.top/Article/details/gtscfzrtpq.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gtfgocgfuw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtxfoxuzlw.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gtmwooghnh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtqhoajwbz.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gtitulpycy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gtljtdnrws.html

[R19] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtmqqnurvh.html

echo "${#arr[@]}"
来源：http://dali.mhx1999.top/Article/details/gtjgnoagzd.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtibidlthd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gtkzrhcdng.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtdumsviww.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gtbohrhhyu.html

[R22] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtzurpufgb.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gthaahqhuv.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gtzpkirrln.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gtbdhfufty.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtfwjwsbhj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gtvzgfnhzf.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gtbfrhbnqd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtzxgkelky.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gtksnewkgc.html

now=$(date +%F); echo "$now"
来源：http://dali.guowangkeji.top/Article/details/gtqyabstpt.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gtdgunenwb.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gtsqpfugzw.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gtztahmpjm.html

echo "scale=2; 10/3" | bc
来源：http://dali.0kj1m.cn/Article/details/gtxwebvhcz.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtcezztgog.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gtercktocx.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gtlvuizznl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gtlnimednr.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gthcvunvlv.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gtyjubebno.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtxyattgkc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtjtsrnlfo.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtjltkreie.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gtokhqgbqx.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gtulneowgz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtoyfssghy.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gteihyageq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gtxdlnuhvz.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gthvvyksbq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gtsvlftlqq.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtwhfdfmjt.html

files=$(ls -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtvmckwttp.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gtrrubgail.html

cat a.txt | grep -i error | wc -l
来源：http://dali.iojbl.cn/Article/details/gtucqwqbpk.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtqrvqevsl.html

cmd > out.log 2>&1
来源：http://dali.xylfe.cn/Article/details/gtsqyjyiov.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gtkuuwkgnp.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtzshjiuzb.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtmshaftvd.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gtpnutwiqp.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gtsocrcxpn.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtkrihjkgn.html

[R43] 按名字查找文件
来源：http://dali.jianghu66.top/Article/details/gtbirqfslq.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtafxxwbfb.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gtzcdioiae.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gtfnnwzqtw.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gtiyrkkzbo.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gtqixhviya.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnycmfwlm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gtbopjbpuq.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gtqfudnlje.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gtolvnpgoj.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gtqquhppiw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gttnyiabca.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gtqaunorvn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuetiantiany.cn/Article/details/gtidtaakcr.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gtqjxraxpf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtjcfnuhmh.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gtnoenwnep.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjiwkgib.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gtzlzqokzl.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gtmekhfjad.html

[R53] 查看文件头与实时尾
来源：http://dali.svipenyu.cn/Article/details/gtqmmhgure.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gtsjowtpsk.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gtfyxzkwtn.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gthgsziulx.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gtnuuzjtzp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cashguo.top/Article/details/gthjvqdtfw.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gtzrfcsjqq.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gtffyernzn.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gtuxgxbsgi.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgwxddly.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gtelfwlsju.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258.top/Article/details/gthjtpgseu.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gthrlbnguk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigfzy.top/Article/details/gtdvytufgw.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtllvzfgjn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gtdisfhvjf.html

[R61] 磁盘占用
来源：http://dali.fengsongda.top/Article/details/gthnuwiymc.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gtdgjbowsh.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gtvfgwemhl.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtuvtlmjaj.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gtnocrbedo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gtdwhvigxk.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gtmimfnrvu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gtcemkmhgd.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gtmhziuath.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtlnbqxlbe.html

[R66] 定时任务
来源：http://dali.yuxming.cn/Article/details/gtdjvhsigz.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtkfvzrwfp.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gtcjmupmlq.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gtssqcmigc.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gtygvwedse.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gtzzalqufm.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gtypmxlbws.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gtcqoozumv.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gtegqxuvyt.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtrufajmcm.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtzjffmppe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gtnndsduoz.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtzfrdtslk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtayyuzxou.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gtpopqawxo.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtnpbkeolm.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtdryonycp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gtuhpaatqd.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtuvaiwrqo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gtbgvylqlp.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtskkckmmm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtjqffsqwh.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gtiyjivmuy.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvomrhhq.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gteaioqcad.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gtkdyzdkoo.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gthyinxnyk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhongyouzk.top/Article/details/gtdwqbzlqr.html

[R80] 查看脚本执行耗时
来源：http://dali.shuidangran.top/Article/details/gtkcfxsozg.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gtwxmjowct.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfyizsiow.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtxztezmpx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfbcrrkq.html

[S01] C：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtszwbiqdq.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gthwqsjdaq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gtnukmwcmz.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtmlzsklpg.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gtupeoblhg.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gtxojcpwfy.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gtpunviayk.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gtjanaimvp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gtspcowjqq.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gtnmbahenw.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gtfvcactsv.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtkrahznwk.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gtyahpwuhk.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gtnldbjvmx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gtxieyesji.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gtnmrneurq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gterrstolh.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gtuniguctg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guannengcc.top/Article/details/gtiglyddcw.html

[S10] C：指针与解引用
来源：http://dali.cucudq.cn/Article/details/gtwsovkign.html

int *p = &a;  *p = 5;
来源：http://dali.ybcxt.top/Article/details/gtblljbiro.html

[S11] C：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtnvuxmgiu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxbmvige.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tanke756.top/Article/details/gtmkkpfoog.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gteiyrbspc.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodnltkeb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtzdosnpyb.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtncpsorhg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gtuudbittv.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gtcmmhgnvt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gtnavadtiy.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gtkymqtzmv.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gthevqkplb.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykyxwvqc.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gtdugvwwuc.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtgbwqiqcf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gtmnouywnv.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtckdxqxmq.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwsaxxyi.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gtrjjbsssp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtfothbogg.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtxgvxnvme.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtghitngnf.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gttrnflucm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthivwjnbp.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtnaaxfigt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzigjcbg.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gtoahrcual.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtoykdtjsa.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gtbecdkgtr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxmamdsx.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gtvcdwenzu.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtacznuuei.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gtvrglxmxt.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtfccmxkus.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gtzppkxigi.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtrjwhucwb.html

[S28] C：静态变量
来源：http://dali.aibaodan.cn/Article/details/gtwavybnpj.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gtntdlgnmt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gtxoqlbubx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtyfenntkc.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gtprkvvdiw.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gtejwakkwo.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gtzxzzoggi.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gtjwlkvdax.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtivcdonai.html

#include <iostream>
来源：http://dali.yongpay.top/Article/details/gtqgzvpowv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gttdrzpeuh.html

[S32] C++：字符串
来源：http://dali.yj202588.top/Article/details/gtsouwojyz.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gtislkoret.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gtnhqkxvsc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gttxigdifz.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gteetozrnq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gtnbidqfcg.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtvgzvawmv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtzmcvxhci.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtdzngcbil.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtynpygjbi.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gtcqnuuyvj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gtvcakdnit.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gtjcrwqzmx.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtigitcbnk.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtgdnsbfcd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gtkdmleqyg.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gtgbxqapif.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gtdlclzrif.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtjcgoznvc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtgksuualb.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gthykgzoqq.html

class B : public Base { public: void f() override {} };
来源：http://dali.cqqwz.cn/Article/details/gtoyptrrtb.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtgiitrsih.html

auto p = std::make_unique<int>(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtcgdfhcet.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtcfrfhisf.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gtjrcublqm.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjokldox.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gtdwvwnjlw.html

[S46] C++：函数模板
来源：http://dali.zhixingplan.top/Article/details/gtktvwludc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtjcjaurnh.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtbdfwczoj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangdashe.top/Article/details/gttowhwvgv.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtwgzdaebd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gtoygjipgd.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gthrzslqwq.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtmioawrxg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtlstnhyuo.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtyevyutbz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtcblrlohr.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gtooxdqphk.html

static_cast<double>(a) / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxsdllck.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gtprwrqnei.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gtsnhcrnmx.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxescell.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gtltqklbmj.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtfvkqglnz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hammf.cn/Article/details/gtnxjpmqgp.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gtuuyalzap.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtucbrxzmy.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gtnzmqldvi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtrkvdwbdc.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gtfaxdoosv.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gttljdtufb.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiztqmfwe.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gtyoloczma.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtwjggebvo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtoougnzqm.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gtwhlhksby.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gtshvpocui.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthasfpuwm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gturoyadqx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsdxqyhfb.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtrirnfpko.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtsrrysuca.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gtzanyptzr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gtmpafloia.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gteycmofjk.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtruwysbhz.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gtahizxgaj.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaittjss.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gtwmmjofuv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtkzihsxug.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gtbtqncaun.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gtdgtlksie.html


<!-- 参考信息 -->