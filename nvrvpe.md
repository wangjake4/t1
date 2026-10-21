代发 wailian999

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtxhfryiit.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gtukdlqhcp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gtjyyffima.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gtdikhtrft.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gtzfwgvjwt.html

[R08] 数值比较
来源：http://dali.c1oappe.top/Article/details/gthnnuacgc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gtmdcbexfl.html

[R09] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiblrpgh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtiyzcfdrh.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtiqnwvsbz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gtnqjrqnkg.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gtysdwzglb.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gtlgliuwkn.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gtqwmnyraj.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtxzjwbgrw.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtdcjzjonu.html

esac
来源：http://dali.gzhubu.top/Article/details/gtgjmxltyy.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gterodnunr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gtkqictxim.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtqpjranpp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtuwpqzqun.html

[R14] C 风格 for
来源：http://dali.ehwqpu.com/Article/details/gtogbqoiuy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gthcoxqhqp.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtjfvwiohr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtwujypyde.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtqurgdgoo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gthawfqdey.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gtgzovpubn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gtzqoctqei.html

[R18] 遍历数组
来源：http://dali.jinqigfzy.top/Article/details/gtuwvhxtio.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gtfqgsswrn.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtuhunxogy.html

echo "${#arr[@]}"
来源：http://dali.snrcjt.cn/Article/details/gtzpzrynnl.html

[R20] 关联数组（字典）
来源：http://dali.hysaishi.cn/Article/details/gtcuasbzfy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gtcvvmqjug.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gtrzjrtfmd.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknlvivvx.html

[R22] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtkvsoavvt.html

echo "${s:0:5}"
来源：http://dali.cdnleiting.top/Article/details/gtdophxasu.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gtazygzkiz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gttqievhvp.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtrzrwpapi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ehwqpu.com/Article/details/gtjikchwfs.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gtjdjqjvxw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gtsjmlvzvp.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgprjpaja.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gtsknrjfxe.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gtvkwpbioz.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gtlrydxabh.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtnhuhikho.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gtynoitaws.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtbuobaobl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gtwqwjrczg.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gtxbfievco.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gtuvrbacsr.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gtmpamscev.html

f() { local x=1; echo "$x"; }
来源：http://dali.xinyue.icu/Article/details/gtoadyjequ.html

[R32] 参数个数校验
来源：http://dali.xuanzx.com/Article/details/gtagxdjhfv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtuohobrnf.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gtjcwaqzmc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gtqtsoguqr.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gtpxbpeeho.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtyesoidks.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gtoprmvoui.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gtlmuksnft.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtlgvbfycb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gtyvhcygpr.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gteugrxxid.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtvqywrvjw.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gtijhlcynf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtbxaltxyd.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gtvvvmbrhr.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtrdjidtam.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgntfvhx.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gtrfyubpom.html

[R41] 丢弃输出
来源：http://dali.haohaochexian.top/Article/details/gtvhiykycl.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtpcgbdvvz.html

[R42] 输入重定向
来源：http://dali.sweek.top/Article/details/gtoohapopi.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gtjesjyqtn.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtvhthphwi.html

find . -name "*.log" -type f
来源：http://dali.svipenyu.cn/Article/details/gthksaviwy.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gtjwdvuxzx.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gthigxuqlc.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gthxwyvvia.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gtvhnockvh.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtcdcmspja.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gtwhhkdtdg.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvycttvq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtxbjbtjbq.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtpawdfhmv.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtsltlfggz.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gteoxrgrzu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gtyspxcxqc.html

[R50] awk 求和
来源：http://dali.chenlongwang.top/Article/details/gtuqqfsvpb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtsfmqqvls.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtgzupreck.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtvslcoeol.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtdrvluaov.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gtqzzybohy.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gtvuonkkwm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gttpuwybpj.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtuzhtqttr.html

diff a.txt b.txt
来源：http://dali.quarkkingdee.top/Article/details/gtxypmkpmm.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsqjwbee.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xziqi.cn/Article/details/gtdywvorig.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gthairwsns.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gtsgfrizts.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gtfogefaia.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gtuwpwdtxb.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtctruzoij.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gtdclhovhd.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gtjmgxbffq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gtuqyrpjpx.html

[R60] 只看 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gtqzffvwgm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gtvhkfqnyc.html

[R61] 磁盘占用
来源：http://dali.xinyue.icu/Article/details/gtezsldwhq.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gtyaugsobm.html

[R62] 找最占空间的文件
来源：http://dali.316326.xyz/Article/details/gtfnuvpxwu.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtpvywamap.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gtfphpjuui.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gtdilzcegf.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gtpwaxsxnt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtgqrslgwy.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gtgqguwqaz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gtvssawqhg.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtwotppjig.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gtnoqaxrmv.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gtmavrwvtk.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxdbjjcr.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtkypurnpg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtqpnejwwv.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gtxkoisbmd.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtbonqrqyu.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtlgsccp.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gthcenffgz.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtpwskftvk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gtawtbkcvk.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtvlroxwih.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtxfdhrusv.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gtbgzzvcku.html

split -l 1000 big.log part_
来源：http://dali.zhixingplan.top/Article/details/gtvzkdconz.html

[R74] 批量重命名
来源：http://dali.hysaishi.cn/Article/details/gtafwwzcjp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guowangkeji.top/Article/details/gtqdeyeulq.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtmivzxalw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gtzbxgkxkh.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gtduvylybv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtlyrsyozg.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtxwgyttjc.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gtpwukawfg.html

[R78] 交互式菜单
来源：http://dali.sweek.top/Article/details/gtqvochtdl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hongshengwenyu.top/Article/details/gtloidxtyd.html

[R79] 解析命令行选项
来源：http://dali.redwolf501.top/Article/details/gtaqgxyrji.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtzszydhjn.html

[R80] 查看脚本执行耗时
来源：http://dali.snrcjt.cn/Article/details/gtpqmhfame.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gttfcnkdqj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtokinteki.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gthbuudxsy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtlamaotka.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gttzbulbca.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gtqxbxcnjd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfpmnqazu.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gttswaklhi.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gtwzvriyka.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gteswvkeek.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gtddkoyvmp.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gtkzqwooch.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtebiksmiy.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtffwinqla.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtunbxldjs.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gtqbsxuggy.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gtqtxltqim.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gttciaodwx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gthtepynie.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gtodnqvaxu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gtstybwsny.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gtxjkfzyot.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gtnethhann.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gtlfosnipx.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gtmmdjkoli.html

[S11] C：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtfkrxyvqk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gtmdnmvrjl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gtxkikdbzq.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtmbkseehz.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gtsdqppcmr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtbyovaxld.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtfwgfljov.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtuvxfnxpz.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gtfjbmkope.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gthttxelxl.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gtitcobeon.html

(double) a / b
来源：http://dali.xuanzx.com/Article/details/gtrolffawn.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gtthrxvnsh.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtlgksyldl.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtjmqhavxe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprywqzkf.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtycquezro.html

int main(int argc, char **argv)
来源：http://dali.yongpay.top/Article/details/gtwxzirnvg.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtkuahqoeq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtlkicxrsp.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtezdsghbi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtnpmouybw.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gtacbwrems.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gtzloletoj.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gtikfidzsk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gtrxhyycta.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gteeljzsij.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gtnvurypqe.html

[S24] C：获取本地时间
来源：http://dali.gotoacloud.top/Article/details/gtamuhzfej.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtsbcubkwe.html

[S25] C：内存拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtmhzatlqs.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gtddcnnewg.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gtlafmagsa.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrbmiowv.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gtdixobrht.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtqfyvtech.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gtqunjonhm.html

static int counter = 0;
来源：http://dali.hnqzz.top/Article/details/gtjjafpjuk.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtnenhigbf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ydzc1.top/Article/details/gtriurufbd.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gttazelbfu.html

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gtmtanipia.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gtzxcwadux.html

#endif
来源：http://dali.pycfn.com/Article/details/gtasncxjlo.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtvnarxfgf.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gtkzzamtia.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtvgivgyzi.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gtjcilwtyn.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxinkj.top/Article/details/gtfvxbxqkb.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gtszofxngg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gtpzktrdyu.html

[S34] C++：遍历 vector
来源：http://dali.jlsjyb.cn/Article/details/gtlanfpval.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gtxniazgxh.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gtxejdtdfu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gttnyummdr.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gtqcvwvnop.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtspuxfdmf.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gtdqjfllve.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gtgbmenkcx.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtvkentymo.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtradboyrn.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gtnfcdvmpk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gtzxznbtgm.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gtoueiipce.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gtcarnzaxn.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gtcluqmfgc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gtsufzlebu.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtvkqjspya.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gtimvovzmu.html

[S43] C++：智能指针
来源：http://dali.xziqi.cn/Article/details/gttphjhgtc.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtbztfokos.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcamfjrzh.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gtuiqwfryt.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtszakaodr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gtvovavkgb.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gtvbinteuh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gtchghuxpw.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gtqvchuqay.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gtpvuufbti.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtjywvzvux.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gtgnifjdja.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gtympjfhtr.html

[S49] C++：写文件
来源：http://dali.chenzaomai.com/Article/details/gtiuireccr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gtvriwyqzp.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoknklhal.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gttsokougu.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gttczwqyab.html

static_cast<double>(a) / b
来源：http://dali.jyoumei.cn/Article/details/gtdcdxsqxl.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gtorrpxkla.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtdvanhahg.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtqwylptxe.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gtsdoatfuw.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gtaazgqpob.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gttruvxpjv.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gtzeszhwae.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shuidangran.top/Article/details/gtlathylxc.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gteoetusaq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtquucatou.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtxqsqieht.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gttslulcrx.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gtilozjqub.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gtqgtbzgsq.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gtlufgtopy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gtbyubqflh.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gtpjdmkrgz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtoaafkojq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzxhbgzsy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gtrucmqcgr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxjhqldug.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtxilgdkue.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtnogrlibt.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gtoidylycx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gtlhkkjxen.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gtysobjwto.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtrvryqyyb.html

[T04] Kotlin：空安全
来源：http://dali.redwolf501.top/Article/details/gtdlabtnph.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gtmfuokezh.html

[T05] Kotlin：when 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtwjcuioxz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gtfvczlfbh.html

[T06] Kotlin：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtuamynqfk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gtdofycbzu.html


<!-- 参考信息 -->