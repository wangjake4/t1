代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gtugmurthw.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gtefyhscyc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.mhx1999.top/Article/details/gtgmslpeay.html

[R09] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtbsifyyos.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gtttkfvkfe.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtxqqxsaxi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtfehqvbph.html

[R11] case 多分支
来源：http://dali.zhongyouzk.top/Article/details/gtiwvenmtm.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzxrocab.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gtdkebbreo.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gtaekcdqeh.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gtpaqrlbeq.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtwywvlsks.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gtxahvffpp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gtmggtxajg.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtoyuhrmtr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtupavvzzs.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtacsmsyrx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtlhsllvzn.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtsvttapsu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gtjgzsdpva.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gtgqbigjgn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtxreoljkq.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gtsyaqqhlp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtvfcjmcdv.html

[R18] 遍历数组
来源：http://dali.wangshuangyany.cn/Article/details/gtkomfgkfq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtsvauffuq.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtwudpuvhb.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcbptacm.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtfhdyoqdv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gtijgxcmyn.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtmyoibayj.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gtqnigsljw.html

[R22] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtfntlhyzq.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gttnhypbvw.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtrerohssm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkeavlpi.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtsopcwcqx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gtsbqdwosm.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangshuangyany.cn/Article/details/gtsosqyumw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtozomgybh.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gtgjuttycr.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gtdmubfcbt.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtlqhzkvmg.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtsqpyolvw.html

[R28] 浮点运算
来源：http://dali.tian-w.cn/Article/details/gtdorjnjga.html

echo "scale=2; 10/3" | bc
来源：http://dali.gzhubu.top/Article/details/gtvqxnsvve.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gtzyauiczm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gttdlroeeh.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gtzwewmgtb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gtvhlvjbvo.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gtskfuuxpy.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtfunflyja.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gtjxynzeer.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtzfisdmhs.html

[R33] 捕获错误并提示行号
来源：http://dali.9152youxi.cn/Article/details/gtchaxbicp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxfzasur.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gtfyxevzef.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtoogqymdg.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gtoyyvquij.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gtnltdlphh.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gtqdnkzyhd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gtjvlfvppx.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gtfzuppsvy.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gteuekzsvb.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtriouuzqe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gthwegpaqz.html

[R39] 重定向标准输出与错误
来源：http://dali.nwbrower.top/Article/details/gtveyrwyob.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gtenktnhok.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtjlqrldyd.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gtparlsvtr.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gtowwjmkcq.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gtftbmtwri.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gtvmkogirc.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gtaflrcmut.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gtslhvwbca.html

find . -name "*.log" -type f
来源：http://dali.cucudq.cn/Article/details/gtaajdjsmg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gtvfxdzyjm.html

find . -mtime -7 -type f
来源：http://dali.dashuyun.cn/Article/details/gtxouttyuz.html

[R45] 批量删除
来源：http://dali.hammf.cn/Article/details/gtpxhdunni.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gtjhewuhre.html

[R46] 递归替换文件内容
来源：http://dali.shangyingyoupin.top/Article/details/gtlnoqswlg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ydzc1.top/Article/details/gtyfndhdoo.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gtybmrdsyy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gtjwsapwve.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gtjtmafksl.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtfxwgfqex.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtluwfkqnj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dianchejie.cn/Article/details/gtyqgdnilb.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtorriprha.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gtbonijmqh.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gtxzzwjhub.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gtajnigexo.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gtlcqqkdfx.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtyjnonjes.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtotiuccpn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nwbrower.top/Article/details/gtroyrxyki.html

[R54] 比较两个文件
来源：http://dali.dashuyun.cn/Article/details/gtdzukcseb.html

diff a.txt b.txt
来源：http://dali.jyoumei.cn/Article/details/gtqmwknsmc.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gtonssdexc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gtrvnvwxmr.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gtrkhzjcgh.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gtneolsgae.html

[R57] 远程执行命令
来源：http://dali.aibaodan.cn/Article/details/gtsmjxrcbn.html

ssh user@host 'uptime'
来源：http://dali.gaohongyu789.top/Article/details/gtqjtvvdgw.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gtuppjfrlj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gthxwqognu.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtfxvrnnsg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gtktckcpze.html

[R60] 只看 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gteiyufyjo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.316326.xyz/Article/details/gtywcomufi.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtdijbgzrj.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gtmwtqkiow.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gtqlktunnz.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahkkexzt.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gtnpgqaqby.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gthkgcvcbv.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gtmwsokjiy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hywenlv.cn/Article/details/gtbxqaento.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gtmxupngij.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gtvwadnloa.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtwuwinlwb.html

crontab -e;  crontab -l
来源：http://dali.cqqwz.cn/Article/details/gthzlydodf.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkmhzjbd.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gtehvzghom.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gtflprdbbb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtxcrntgmj.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gthgehgwqv.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gtgxtwbsgu.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gterugwbqa.html

date +%s;  date -d @1700000000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpyndkmy.html

[R71] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtkqgnirdv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gtsivfkwhi.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtpcfpsieq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtifwixynv.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gtkvwjzdma.html

split -l 1000 big.log part_
来源：http://dali.jinqigfzy.top/Article/details/gtkdzgbuzv.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gtmdjhhixa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gtsfvgovav.html

[R75] 导出环境变量
来源：http://dali.cqqwz.cn/Article/details/gtcwdpehsq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtcllzvadt.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtpkuymvos.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtqkjkbwkd.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gtgseyvfoa.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gttumbxyyi.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtrhfdbikl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtozgatkre.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiymvdibk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gtqcaneqee.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtyoqszcfi.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxdadjun.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtahmsiuws.html

S. C / C++ 专题
来源：http://dali.hfpthk.cn/Article/details/gtkkwgngpd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvmcsowy.html

[S01] C：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyvmeyjv.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gtkqefyydq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gtvmixlsjs.html

[S02] C：变量与格式化输出
来源：http://dali.pycfn.com/Article/details/gtnrhwrepr.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmijedbdt.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gtnywhvvro.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gtwzmcbdoc.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtkjcfowia.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomjmfzvi.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtnjozjhgx.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtgcvdowku.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtsjrovcnq.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gtyvwhlecf.html

[S07] C：数组遍历求和
来源：http://dali.zhixingplan.top/Article/details/gtziqqonpl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gtsepovxea.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtfnmhxypc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gtemqtunrf.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gtowvwplkh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtakihvcot.html

[S10] C：指针与解引用
来源：http://dali.shzxlz.cn/Article/details/gthjqcvrrq.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gtfryupafe.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtmmieflvk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtmnuifajb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtkecyaqmk.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtruhszbee.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyhsswhp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtgziupuze.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gtywuupjiv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gtxsljhjkg.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtlwerohxi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gtcmnxeerk.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmtfzsig.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gtjvyxkxiu.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstldormp.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtruvxqkfr.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfgnbzcp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gtvazlfdoj.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtpajvdcxc.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtcmjnynmx.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gtyzeygkio.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtdysuwtms.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gtyfoskipk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtdlydeqbl.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gtsalzblel.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hammf.cn/Article/details/gtritrjofr.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtnencscqn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gtfqsnzdof.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gttrylfgrn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtpeboboiv.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gteatfccgh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xylfe.cn/Article/details/gtsxttdfzx.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtlcicpfal.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gteqtfzjgh.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gtkuvdpgek.html

memset(a, 0, sizeof a);
来源：http://dali.haohaochexian.top/Article/details/gtwagkzpjx.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtpyzacxfe.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtjsjqnhpy.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtadhopxti.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gtwjsrenpr.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gttszhooim.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gthippgbnv.html

[S30] C：头文件保护
来源：http://dali.yueranfly.top/Article/details/gtzdriblye.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gtfcdlrdxu.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnsichiv.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gtkusglfix.html

[S31] C++：Hello World
来源：http://dali.birdmap.top/Article/details/gtnvskizai.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtkrcozzil.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gterkyqjjk.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqxugrhg.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gthdvsezez.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gtrpkhundf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gtxcxxarci.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshpbamgv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtkzkurxvl.html

[S35] C++：map
来源：http://dali.andypj.xyz/Article/details/gtorfdeqdy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtmpzmnuwp.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gtjbefcoav.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtddiaiusl.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gtpkczarsd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gtbvisogfa.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gtpcqktfwc.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtqlztzpdq.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtwstnbqmr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhixingplan.top/Article/details/gtnrbzdcrl.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gtlbnqbqzc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gtzvrkuheb.html

[S41] C++：类与构造函数
来源：http://dali.ydzc1.top/Article/details/gtldugxvsj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shuidangran.top/Article/details/gtiwjrhnnz.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gtmsfwpfed.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gtvtvaaodc.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gtrgctemga.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnvfjhvy.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gtuizzoggu.html

void inc(int &x) { ++x; }
来源：http://dali.mhx1999.top/Article/details/gtxzeyebjn.html

[S45] C++：lambda
来源：http://dali.havefunace.top/Article/details/gtzhlmooqa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.redwolf501.top/Article/details/gtmwnzgryx.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gtpacqlzye.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gtvppxezly.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtkvpefmzs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtkdpssqzv.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtvtojnnou.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gtvmkdljgo.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gtljdnotpq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gtsrezwrsp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gtwwxitemr.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gtoyrjfdpq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtnadewujy.html

[S51] C++：显式类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtljmzehqt.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgmompxn.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gtyrhicixh.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gtynoylwny.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtsdphwfys.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gtixhreoqk.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtqoicblgb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gtkppnmpmi.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gtqnauopst.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gtapkxtvak.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gtduqbsmeh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jianghu66.top/Article/details/gtfvfbsvbg.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gtzvfuneno.html

constexpr int N = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtmwargrxx.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtykgucslu.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gtgyoqmnvd.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gtpbhcadpv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gtrokajhlf.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gtlelhabbw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gtqqxfljys.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthddfhlnn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtgolffokx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqekdnwag.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtdbjdqspw.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtthlohwef.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsfbkhxj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gtqfnilwuj.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtuxxntxwz.html

"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtzklmelta.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gtlprporsn.html

val n: String? = null;  n?.length
来源：http://dali.xuetiantiany.cn/Article/details/gtmmpczbnl.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtvcaijofz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gtdgpmzezw.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gtvysbidxq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtyrbikdwz.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtgudmrlox.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbszuqod.html

[T08] Kotlin：数据类
来源：http://dali.sufxvd.cn/Article/details/gtdfrxjmiu.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gtgwnbmttv.html


<!-- 参考信息 -->