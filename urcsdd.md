代发 wailian999

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gttrqejjzt.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtcrhevxqq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gtzsbkotoo.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gtyqfamykj.html

name="${1:-default}"
来源：http://dali.aibaodan.cn/Article/details/gtbqldlrtc.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtaoyjenho.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtvkvitjls.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtzvkzvzqu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtilimutdr.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtxblbmynh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gtlagtgtjl.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtowvlfyno.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtawqmqkzq.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gtczwopznm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtiabvmkem.html

[R11] case 多分支
来源：http://dali.ehwqpu.com/Article/details/gtwvlrjdyj.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtmfllpeig.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtzdsfdkby.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytqxinlw.html

*)     echo "未知命令" ;;
来源：http://dali.jianghu66.top/Article/details/gtmtyriqte.html

esac
来源：http://dali.mhx1999.top/Article/details/gtxtkqzntg.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gtwyzwfsie.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxkxqjlu.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtntqqznzp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtayxkjuqt.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtxuipklgg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gticoyrvnb.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtuopsjuon.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuanzhike.top/Article/details/gtkavxsdnw.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gtrgxbmolm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtltpfjcwp.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gtyuklsncv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtbeuxbmmf.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gtktcnnbad.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwmghljh.html

[R19] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtudlizwtf.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gtztlszwfh.html

[R20] 关联数组（字典）
来源：http://dali.hnxiangtu.top/Article/details/gtxeuobsqu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtgdmqqypc.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtesuspybb.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtyczmuiat.html

[R22] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtzjlvvqar.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gtgrmzroav.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtytcqunhi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtnkhjhbio.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohrethkw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gtvjyffvuc.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gtmncawmnc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtqrhchwpg.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gtiskumwvl.html

now=$(date +%F); echo "$now"
来源：http://dali.cheryme.top/Article/details/gtlqqzlqht.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gtiofzkhxb.html

echo $((1 + 2 * 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgowdzxae.html

[R28] 浮点运算
来源：http://dali.cashguo.top/Article/details/gtgujfyfhy.html

echo "scale=2; 10/3" | bc
来源：http://dali.ybcxt.top/Article/details/gtszrphmjd.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gttrijvlwj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gtfvdujrov.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtasfrdntj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gtdgbdocag.html

[R31] 局部变量
来源：http://dali.fzhhl.top/Article/details/gtxwwaznca.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnyzpano.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtabjddopm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtadqjamwt.html

[R33] 捕获错误并提示行号
来源：http://dali.gotoacloud.top/Article/details/gtgnuhbkcj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gtxundimca.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gtxqflbwnv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtagbriykp.html

[R35] 后台执行并等待
来源：http://dali.yj202588.top/Article/details/gttqzmwphq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtftpcnezf.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gtspkduray.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gtkntpccsk.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gtqgnuhmgi.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqvtthkqi.html

[R38] 管道串联
来源：http://dali.chenjidiqi.icu/Article/details/gtxixjbnuf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gttnaehapm.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtczxrwgde.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gthihtbrcl.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gtqcsnefbi.html

echo "log" >> out.log
来源：http://dali.daxiang520.top/Article/details/gtlssoeobm.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gttqvdysgi.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gtyfpstrxk.html

[R42] 输入重定向
来源：http://dali.xziqi.cn/Article/details/gtaolajxld.html

wc -l < a.txt
来源：http://dali.sxryk.cn/Article/details/gtxnsgkoce.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gtgozublde.html

find . -name "*.log" -type f
来源：http://dali.yueranfly.top/Article/details/gtlraqdtrs.html

[R44] 按修改时间查找
来源：http://dali.gotoacloud.top/Article/details/gtktkxlylj.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtrgxvdcpd.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gtduvmmpwq.html

find . -name "*.tmp" -delete
来源：http://dali.jqgfzy.top/Article/details/gtufyorhas.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkyxheqh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gtmlfntsgl.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gtomeqsexk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtzdycorae.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gtstmvsjaf.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtmskurifv.html

[R49] awk 带条件
来源：http://dali.yonumen.top/Article/details/gtyesrigyv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gtwzmimzag.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gtkkpyisgx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtfvzqzwnj.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gtfuvnibrd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtopavttvi.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsfjatsp.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gtndyoueij.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gtnzgyreac.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sxryk.cn/Article/details/gtmpziktag.html

[R54] 比较两个文件
来源：http://dali.xuanzx.com/Article/details/gtmgjpsang.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gtoypujjke.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gtknrsagzb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimdhrwpv.html

[R56] 远程拷贝
来源：http://dali.iojbl.cn/Article/details/gtavaxxfdk.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gtqzuyxjpf.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gtaabqjwxn.html

ssh user@host 'uptime'
来源：http://dali.sweek.top/Article/details/gtbggwqhyu.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtnzxilezi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gtsekzohlg.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtyrgkxmry.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtkphxafwt.html

[R60] 只看 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtzuxhssoe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gtegwpxbua.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gtozrvptih.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gtmqhptunb.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gtiudugtmo.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gtireljffw.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gtqlrvpmmm.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgfzy.top/Article/details/gtpinhwojf.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gtqqdszvvl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtayxwhesu.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gtvhptjtyz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gtbgxafgyc.html

[R66] 定时任务
来源：http://dali.vqdsnc.cn/Article/details/gttjgpldia.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbisbccx.html

[R67] 生成随机十六进制串
来源：http://dali.haohaochexian.top/Article/details/gthmmrmxdc.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtaglnzcdm.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtrlskcdua.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gtjymknfuw.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrrhsvru.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gtxzoqwxzr.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gteyfoqvmw.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gtbggijgdi.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtbkpduaft.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtaazvwhbu.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gtzpvhdylj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtbhcafqhu.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gtszsmhtky.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtaembwpnp.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gtkuaylblc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtfzqvtwni.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gtsmameltf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtmzzcohmt.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gtxukkmnvv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtyjtrpzuz.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gtfqiakcjf.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gttgdeglpl.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtudlviafj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gtlnwjcfit.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidjixihf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gtygqiproi.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gtqslahgkh.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gtxdnyiuqf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgzalvnkz.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gtsivvlqmq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtywjsnyza.html

[S01] C：Hello World
来源：http://dali.snrcjt.cn/Article/details/gttiujoroa.html

#include <stdio.h>
来源：http://dali.jinqigfzy.top/Article/details/gthneiiszm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtoropxpsy.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gtxqittctt.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtgfjivonh.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gtvtprxsyq.html

int x; scanf("%d", &x);
来源：http://dali.andypj.xyz/Article/details/gtqeqmdeyg.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtvqlztoed.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.andypj.xyz/Article/details/gthfszwmqk.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gtnmsxitvv.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gtvcqfqbek.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gtpcxqxipg.html

strcmp(a, b) == 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxhkckmb.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywvsfrix.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cucudq.cn/Article/details/gtgzfqkyuo.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gtgdjhhist.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gtjhrtilwm.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gtmlgigkgo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gtdueztvjw.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gtnndnzcuu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gtabmfqtxt.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtzvkfhpln.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gtewtmnukz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtxpitkljh.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtfvhocycv.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtpbaauzbm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtgzmptflv.html

[S13] C：宏定义
来源：http://dali.xylfe.cn/Article/details/gtyhwkdyzr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtcaectplh.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gtglexwxxt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gtmkyfuijm.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gtbkriypml.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtkzolkisw.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gtsffzjpff.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdsyuxvc.html

[S17] C：安全拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gttnnjwujo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtksupohxc.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gtqhbsmpsl.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gtokjuakkt.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gtqxavakqb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtpdkvwjmr.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gtzxvkhakf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtejcwjzca.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gtiaijbhmf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbqxpsty.html

[S22] C：字符串转数字
来源：http://dali.cucudq.cn/Article/details/gtiypxzzsa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gtsgmlfyny.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gtyaviubxp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gtiwzkvrib.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gtzdlrdafj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gttinmhggg.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtuofgssdp.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtgfbvmiyv.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gtpggrcvze.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gtihcqxnie.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtgiqtcblx.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtikwcbkap.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gtximalzmg.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gtppveleye.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gtyjjeyisx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtmbvtzcue.html

[S30] C：头文件保护
来源：http://dali.jlsjyb.cn/Article/details/gtagfucjsu.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtdhubixry.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtlvmloays.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gtarwffxwx.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtihglrbuk.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gtsqeiacsa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gtcanplbeg.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gtzvnfhryn.html

std::string s = "hi";  s += "!";
来源：http://dali.hnqzz.top/Article/details/gtflpvfztj.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtrttdtcuw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtexpzxruf.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gtehmxktfk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gtxvogroki.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gttfkrpbyy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtnmjtrcdt.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnekvkth.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtviglcxse.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtjldifzrf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtldiymhfw.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gtemapktga.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtxbtycare.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gtwxywiekg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gtdqhlrwpc.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtbwbcoeem.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sufxvd.cn/Article/details/gtsitbrglv.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtbkmmjdyh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gtdjxipcur.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtdaoktqef.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmumszrhl.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gthmtvejph.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenzaomai.com/Article/details/gtgxkznioc.html

[S44] C++：引用传参
来源：http://dali.aizwys.cn/Article/details/gtkglaixfm.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gtwyyiotvb.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gtfpliuchk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gtvturxark.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gteufnuadv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gtchuuafyk.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gtgyfyoubk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gtuatfienf.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtpedrpiqe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrafrajsh.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtrdqeplva.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gtdvixpdew.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtnywrgveq.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtplbcqneb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtpjpmgozi.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtqedkywli.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gttfgnmtjt.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gthoqqshxk.html

int size() const noexcept { return n_; }
来源：http://dali.hammf.cn/Article/details/gtjbrgxsbs.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtjpflukjm.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gtxqzeujnm.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gtqelsbjux.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.kuanghao11.cn/Article/details/gtezxmiyev.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gtnovfkfmu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnqzz.top/Article/details/gtphsmuzvy.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtxvtvwqwk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtlxrpulca.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gtxkjcuulc.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gtbdjuyjhm.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gtipahzdmi.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gtiofvfqsk.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsufbdkcm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhongyouzk.top/Article/details/gtxcpiehts.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtupwpylsl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gteuaegknl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfbehlkym.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtjsaekqpn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefzahdkd.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtyrsbxknw.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtsocswdzv.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gtcsnsvogq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjdznzms.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gtyojauohu.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtuxleblow.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gthdgokjtl.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gtxishzwub.html


<!-- 参考信息 -->