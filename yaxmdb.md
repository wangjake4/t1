代发 wailian999

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gtttnngapt.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gtdszwrpqc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.meibo888.top/Article/details/gtoasqxxkw.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gtlruuckmm.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gtmuympmpi.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtlhpiczav.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthytuebpn.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gtkvacjxdi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtqxaqmtis.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gtrfmwilcc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gtcksmmzfv.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtdcbxnz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtoqfazcoq.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gtipnkqxbh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gtudfogpfh.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gttgcnlvok.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gtzmqoecsf.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtzsbqkspz.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsckiknx.html

*)     echo "未知命令" ;;
来源：http://dali.9152youxi.cn/Article/details/gtgfzwszgg.html

esac
来源：http://dali.jinghuilouyu.cn/Article/details/gtecmthjrp.html

[R12] for 遍历文件
来源：http://dali.aibaodan.cn/Article/details/gtrgfaxzrn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gtfnuorxyn.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtbtutxnmx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtwlhpooni.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gtbtwrnqap.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtxsthhbbr.html

[R15] while 逐行读文件
来源：http://dali.316326.xyz/Article/details/gtnnwrohfm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gthacgnnip.html

[R16] until 等待条件
来源：http://dali.nanxuanxn.top/Article/details/gtevhjzjuf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtzhadjxed.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gtitxbmqfu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtanzgolnm.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gtrtuxsaal.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gtrgnaeodr.html

[R19] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtamhwxpqi.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gtdixynuvw.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtvveqzpjd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gtdqykjyrm.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtmrbaaqar.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gtsteyihca.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtbnqpawvx.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gticujkjzm.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtlnjkizlu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gttosfhtyk.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtefgxklgz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gtmniktmpd.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gtbzedisur.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gtuzonzjjb.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gtfigofhjn.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gtvnuvubuw.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gtzuyakdpy.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gtkuftajhs.html

[R28] 浮点运算
来源：http://dali.jinqigufen.top/Article/details/gttfcdnply.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenzaomai.com/Article/details/gtecxwlmwb.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtqgdnegzu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtlhjxxbga.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtdxqlsrdu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvdjqxar.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtoyuulaho.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gtqutvlyth.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gttxqxgspw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtqnfkhvxu.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gtverqjmyr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gtjbxtwtrp.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gtxytvrhsh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtzeavwiyp.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gtkfepivzt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gtvtstpvif.html

[R36] 并发执行多个任务
来源：http://dali.nanxinkj.top/Article/details/gtvoldaqje.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.haohaochexian.top/Article/details/gtekpmmolf.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gtbjkpmhsp.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gtyvnwmcif.html

[R38] 管道串联
来源：http://dali.svipenyu.cn/Article/details/gtafrxybnw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yueranfly.top/Article/details/gtlaoxxvjq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxivcetj.html

cmd > out.log 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtplzlkonu.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyegsotk.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtijxwapqc.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gtqjfoahfk.html

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtjszkceyc.html

[R42] 输入重定向
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhprorkp.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gtltixwhct.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gtgwattiue.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gtvywjsmtp.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gtoffwiahz.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrhzfxfw.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gtmdxeters.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gtowreuttm.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gtudunpqwc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gtxdnyvxdk.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gtjtjciify.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gttdwwnpcd.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gtbnmsjbgf.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtjtxwrqiv.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtqmttkhwf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslhyoowl.html

[R50] awk 求和
来源：http://dali.cheryme.top/Article/details/gtiofghrpu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gtlzujsxir.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gtzfwdecqp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gtwnmtavbh.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gtomtlnbds.html

wc -l a.txt
来源：http://dali.daria6918.cn/Article/details/gtdurgpsiu.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gtbrxylqhi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtpshonyql.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gttomymuno.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gtwekzinjd.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gtawqvgtqx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gtjlumzbmw.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gtgtrjqeiz.html

scp file user@host:/path/
来源：http://dali.0kj1m.cn/Article/details/gtbjqlazpb.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gttxgxfbsk.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gtewklsygg.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtezploeie.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gtxrsfdsmu.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtqmdkgqaj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gtmcqmcczx.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtnafhfmme.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzpgvnct.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtdhjvwbrp.html

df -h;  du -sh *
来源：http://dali.sysykeji.top/Article/details/gtwrlzbeza.html

[R62] 找最占空间的文件
来源：http://dali.sufxvd.cn/Article/details/gttzsesnfd.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gtguviobqh.html

[R63] 内存与进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfxwyzyw.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gtvrvwnani.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gtzuabbdtt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtslqgltmy.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxexjeds.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gtzkwzavmg.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gttjdtdude.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gtmyseheec.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gtycwtgayq.html

openssl rand -hex 16
来源：http://dali.hnxiangtu.top/Article/details/gthrqlfkep.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gticsvzgcw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtdhtkdorn.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtsrohatsu.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtuqmokglr.html

[R70] 时间戳与互转
来源：http://dali.snrcjt.cn/Article/details/gtplzcsvuk.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtnvcqngop.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtbvvmgncc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtxxsvedwp.html

[R72] 等待端口就绪
来源：http://dali.redwolf501.top/Article/details/gtgewyrjfu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtitgxgdno.html

[R73] 分割大日志
来源：http://dali.hongshengwenyu.top/Article/details/gtmrgtirtu.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gtqlbtjqra.html

[R74] 批量重命名
来源：http://dali.cqqwz.cn/Article/details/gtscdrutbs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gtjsqoihza.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gtpqgbozvt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gtmfefbwqn.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gtwopakcjd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtklnkadmk.html

[R77] 读取用户输入
来源：http://dali.yj202588.top/Article/details/gtejjyqcte.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtquzvzgnj.html

[R78] 交互式菜单
来源：http://dali.andypj.xyz/Article/details/gtqyfndclx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtromryfho.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtkzollcvw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gtsokorawa.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gtbiapksiu.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gtahphtckn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkbkksqcz.html

S. C / C++ 专题
来源：http://dali.kuanghao11.cn/Article/details/gtejleupyj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtueaoethv.html

[S01] C：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtwggdasac.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gtdnxgxcif.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gteabnwxwp.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtarubpcma.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtqyfrxifs.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtjdmdzlcu.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gtkibopnbp.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgatgzmhy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gtuckrhhel.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtcyzqcnbz.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gttrxyndbh.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtojhvccsp.html

strcmp(a, b) == 0
来源：http://dali.shuidangran.top/Article/details/gtabuehgel.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtmhawdmnf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gttuiiybjm.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtjtbfoklq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gtnljekenv.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gtdoztvioz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gtcthrklbl.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gtimcptkad.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctlnuxcf.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtwlttgnel.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtadovxmvr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtfwvfhqrs.html

fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtoszdnnyp.html

[S12] C：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtypishnef.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtnwbzdaio.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhzcural.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tian-w.cn/Article/details/gtakxyeobf.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gtlyqqkkoi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gtnfcpwnwh.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gtqqohqnod.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gterqgecsc.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbmmnjxi.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gtdojitngq.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtaucnkvxi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gthraygzsj.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gtqisumali.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtivssvjmv.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gtijvreusa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtcsztahyo.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gtuxkfzlva.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gteaqocrfn.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjmwgjrs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuxjtknn.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gtajdzqylt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtofusuwpk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gtsbietdli.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gtjbdyoflx.html

[S24] C：获取本地时间
来源：http://dali.zhiwuduotai.top/Article/details/gtrifdmxkq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gtylivvnhr.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtxpmrswjx.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gtdybihyej.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gtfudvtjbn.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gtupefchch.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkkfmrjh.html

const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtlspmrtvn.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gthveozbsv.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtpxztyloa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gtzxfhsfgc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gtxurtqpoa.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gtwkbdhlmw.html

#ifndef X_H
来源：http://dali.kuanghao11.cn/Article/details/gtuiywxkfs.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gtynhjlmmq.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtydjqoypj.html

[S31] C++：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtrbrimoxm.html

#include <iostream>
来源：http://dali.hnxiangtu.top/Article/details/gthgdsmdbb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtmoiqojfk.html

[S32] C++：字符串
来源：http://dali.zhixingplan.top/Article/details/gtlawyfiqt.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gtscxwkwpa.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gtwribfwzc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gtpqmaiaeu.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gtywaltseo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqvxuwyr.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gtxtknxkxc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtboypfocu.html

[S36] C++：unordered_map
来源：http://dali.kuanghao11.cn/Article/details/gtnzzfkwbn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtwqowpvhw.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gthnqiqpkw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gtzipsuljr.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtjtnzoerl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtkneophah.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtggwqhdfz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gtmibvkjry.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtwsqkqdcw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzoerebc.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gtxsswkyjx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtmeqjuzjz.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gtwmknkaku.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gtnpmlxfiv.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gthgbqgorc.html

auto p = std::make_unique<int>(5);
来源：http://dali.smart0.xyz/Article/details/gtskslwzhw.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gthwpjyevd.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtxacbmven.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gtbkazlqfg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaoxiqml.html

[S46] C++：函数模板
来源：http://dali.jyoumei.cn/Article/details/gtkujvkcqe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwhsoqnk.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gtoyryfxhh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gtbaqwgrlk.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gthlovzbew.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuetiantiany.cn/Article/details/gtwhmwkopg.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gtotqldoek.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gtxlrxpwpf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gtugmobmha.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtjxrjmzxe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gtusgjekgw.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gtrihbuend.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtjexmasdn.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gtrpkrmlnp.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gtdgtrqsml.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gtrueqijsf.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gtiugxvley.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gtfzzcuycf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gtpysddzvm.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gtptfnceof.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtzqgsuehz.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gtqbdgbxxe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gtflaaxqni.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gttvckdvzw.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gtpjjlxnpl.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gturynpact.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtvntqvjko.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdevpqbye.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gtxfsnwaoa.html

[S60] C++：遍历并删除元素
来源：http://dali.haohaochexian.top/Article/details/gtydqmxspo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gtflhskgpu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtybgylzgd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtyfisaere.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnzcjwqzs.html

[T01] Kotlin：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtylrktlgn.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtkodrzvyq.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gtzgtlmqoo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daxiang520.top/Article/details/gtivpqbfoe.html

[T03] Kotlin：字符串模板
来源：http://dali.jlsjyb.cn/Article/details/gtlygnqifr.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtywtlqaxr.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtfyivpeus.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtwjitquya.html


<!-- 参考信息 -->