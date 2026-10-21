代发 wailian999

name="${1:-default}"
来源：http://dali.snrcjt.cn/Article/details/gtudjhrhbu.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gtkhqpdgxn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtuuijrsym.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gtkgoaifge.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gttnfkiqiu.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gtcjjjzgsj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gtaxpdtcge.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gteciasshv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gtgkluuvel.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasreuehi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gtxuannwal.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslosdwmp.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gtqhtnlous.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gtkbwbcxcb.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gtyzuvaqqo.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtsovawrpk.html

esac
来源：http://dali.fzhhl.top/Article/details/gtznedphet.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gtdfamevpf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtszmmappb.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gthxssduls.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtdsudhxgc.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gtflrhwaan.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gttqrzbwjj.html

[R15] while 逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtnbnojcid.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gthgyqjzbr.html

[R16] until 等待条件
来源：http://dali.andypj.xyz/Article/details/gtnusffmbf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtpcakrrgd.html

[R17] 数组定义与取值
来源：http://dali.redwolf501.top/Article/details/gtlumlllec.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ivvv.top/Article/details/gtdgewhxfr.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtyfpgucdh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cheryme.top/Article/details/gtgxxdlzbl.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gtjxdmtbxt.html

echo "${#arr[@]}"
来源：http://dali.birdmap.top/Article/details/gtqkqthuhm.html

[R20] 关联数组（字典）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqxuetzz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtuadyxcni.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gtwaqerqgw.html

echo "${#s}"
来源：http://dali.gzhubu.top/Article/details/gtzrmmuqcq.html

[R22] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtdxbwakqb.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gthaosirrg.html

[R23] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtfyvgbcwd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtztrrggui.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtcmemkhjy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtffdnwjrf.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gtntjclyhj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gthjxsyglu.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gttgxauqcn.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtzufbjzte.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtautsrmnh.html

echo $((1 + 2 * 3))
来源：http://dali.feifeiyinyue.top/Article/details/gthbapxyyu.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gtgyedhfpj.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtrginbwwu.html

[R29] 定义函数
来源：http://dali.ydzc1.top/Article/details/gtlrvluslv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gtiwcefkmi.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gtqmjbqldv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gtflokraco.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gtleabxmyo.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfilfcbkm.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gtfdnmtumc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtgpjojlnt.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gtwannpayk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pengpengdd.cyou/Article/details/gtwfaasjpz.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gtthnwuifv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtqfldfwla.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gtncsrqlxv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtomifcamj.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gtdpswrtav.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gtgchvlrou.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtpukujrth.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gtdpbpukyn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtjetzdlxb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gtyprvbuhp.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtjnkymyxf.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gtifjdyzdx.html

[R40] 追加写日志
来源：http://dali.pycfn.com/Article/details/gtmgaxoybh.html

echo "log" >> out.log
来源：http://dali.cucudq.cn/Article/details/gtsbeknsxm.html

[R41] 丢弃输出
来源：http://dali.pengpengdd.cyou/Article/details/gteyioljpg.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtpwgkaaow.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gtkedtquad.html

wc -l < a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuxqzapp.html

[R43] 按名字查找文件
来源：http://dali.aibaodan.cn/Article/details/gtihcleuec.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gtipnvbhoa.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclwhkqbo.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtdxsgvrtj.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtymuxbgsm.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gtnzlmniuc.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gtxhppzanq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuanzx.com/Article/details/gtwgerkfqt.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gtwsdkyxno.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gtprhbqnze.html

[R48] awk 取指定列
来源：http://dali.sysykeji.top/Article/details/gtifowtlgx.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtqburslli.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gtsccuixog.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqprerda.html

[R50] awk 求和
来源：http://dali.andypj.xyz/Article/details/gtppkykzup.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fzhhl.top/Article/details/gtffczhejx.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gtmipkwwtv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xylfe.cn/Article/details/gtmkhakdut.html

[R52] 统计行数
来源：http://dali.daxiang520.top/Article/details/gtgkzamjnr.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtesfafzpe.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gthlpkumef.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gtlhqrgrwq.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gtleiocfuw.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtltgxlcpc.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjldyjzh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gtoptolymb.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gtptoxpypf.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gtdpgywxgr.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gtmigdjzse.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtvhnrpznn.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gtoowfxmen.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gtxauzdwwz.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtfykscbfu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gtqsxqokmx.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtvxgnkutg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gtcbcgaacr.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gtxhsyuvvd.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gtpryfzzxk.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gtfqvrggum.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtavzgdzvc.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gtfopmsaow.html

free -h;  ps aux | grep nginx
来源：http://dali.zhengqikj.top/Article/details/gtseadceuq.html

[R64] 结束进程
来源：http://dali.quarkkingdee.top/Article/details/gtraujejso.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gtqxdqytts.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gttidknehc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gtreimobqc.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gtutkpluxj.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gthutymvez.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gtdweeihnr.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtdmdzaksv.html

[R68] 计算文件校验值
来源：http://dali.hnxiangtu.top/Article/details/gtwpbiuwqy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gtbmpyrsod.html

[R69] 生成随机密码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimvwkalb.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gteosonvia.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gtqkugmlpw.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtdcketinp.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtuezmerag.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtdzdywekn.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovjyjqfe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtiobvxhzt.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gtutefzmzs.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gtuqknvpjw.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtzecyzwsc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gtkwnwqkxo.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gtikukgoij.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shzxlz.cn/Article/details/gtmwqzulkh.html

[R76] 使用临时文件
来源：http://dali.dashuyun.cn/Article/details/gtdkbozgxl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtsaqivrfv.html

[R77] 读取用户输入
来源：http://dali.kuanghao11.cn/Article/details/gtjzdhtbuy.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjpfgvet.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gtlyoknitv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yonumen.top/Article/details/gtdltlrsyr.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gtrflpkanx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtinrqoljj.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gtpmnfdsrv.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gtctcfnbst.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtajdcrgmx.html

S. C / C++ 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtyesurcls.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjrpoxkaf.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gttwgqzrja.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtbkshbyhn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gtuuthcwzp.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtxbhrvjyh.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyeosmkb.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gtbmcggmmr.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gtgzjtutqh.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gtcbwgeoki.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtzoubiypl.html

[S05] C：字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtnaqkpnms.html

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gtxlajothw.html

[S06] C：字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtioulkvrq.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gtocvqbgwr.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gtwbnhuhsb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gtnfgjrooq.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gtcfzmkqqt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthazvsmt.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtekvbczth.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtsonournd.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gtyasoyros.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gtjqhvhcok.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gthpqrrgza.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnqzz.top/Article/details/gthptnrrzj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gtedihusel.html

fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtpzzfkiej.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gtasrzboaq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtnkxjgvfx.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gttnmclesc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gtwflvszgy.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtfxuxxeaa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtusnvsycf.html

[S15] C：类型转换
来源：http://dali.shzxlz.cn/Article/details/gtixssnlsx.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gtfyjxwgpt.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gtlcnalspa.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtjgdravbd.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtdwvuyejr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvianfrmg.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtumdcwguy.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtvglhcsau.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtakzuasqy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmnlixyg.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtspavewcl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtsdiwylut.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gtyncpxvqx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cdnleiting.top/Article/details/gtjekirksn.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvilfowzv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gtzzstwjsj.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gtvakcoyeg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtxmaxtwqc.html

[S24] C：获取本地时间
来源：http://dali.nanxuanxn.top/Article/details/gtvztrzpgn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gtobheqepq.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtxmgqptbd.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gtysqjbbdg.html

[S26] C：内存清零
来源：http://dali.gzhubu.top/Article/details/gtzfyriyro.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gtcufaresc.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvzkmjjc.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gthogwznmx.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtccdoaszn.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gtdusrgozq.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gtpsiuujrr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gtetenzsqe.html

[S30] C：头文件保护
来源：http://dali.yongpay.top/Article/details/gtgilyuczb.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gteyoepdfl.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gtuwfsbzek.html

#endif
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjvxqaon.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtnryhzqpe.html

#include <iostream>
来源：http://dali.hysaishi.cn/Article/details/gtesnzgbbk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gtdsrsdmtb.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gtgkvvkbie.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gtgbfpszfo.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gtkneuiwzu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gtohhirirf.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtjglqfkvp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemjnmcuq.html

[S35] C++：map
来源：http://dali.cqqwz.cn/Article/details/gtmkmnqlkp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtgqayuqrd.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gtcyzbjpdo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtpakqncbc.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gtqwrajvlx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gtzmoeroon.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gtjopjbhpi.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gtgtnqlnki.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gtcodyctgi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtmhpgulwx.html

[S40] C++：查找元素
来源：http://dali.hongshengwenyu.top/Article/details/gtxdgagaxa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gtumoywqxe.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtwieadaym.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gaohongyu789.top/Article/details/gtexuesvht.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtydygtpuo.html

class B : public Base { public: void f() override {} };
来源：http://dali.yongpay.top/Article/details/gtflmkhqnx.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtanamazbm.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gturymrnfd.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtzskhtroy.html

void inc(int &x) { ++x; }
来源：http://dali.gotoacloud.top/Article/details/gtkdsrpvvd.html

[S45] C++：lambda
来源：http://dali.jlsjyb.cn/Article/details/gtnzxatqxy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gtnwmtamvc.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gtafrehowp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gtuhiunycu.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gtqixezyou.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gtpmhhfrjl.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtzdchgfxb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gtzttuevlp.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gthrmwpvqp.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gtodncosum.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gtnxisjwbf.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gtqkrulzgb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtjmvnoyzn.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gtosueakpm.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gtitwyaqbe.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaisnadec.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gtorjkxgtz.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gtejpvynaq.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtahyjoesq.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gttrejhpxy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gtouerdiik.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtyhtddoyd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtlnxdakrx.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gtgdzhdpzh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ppjwa.cn/Article/details/gtnyzdngdl.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gttfxjhqgj.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtdiholpss.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtmltlgwws.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gtcnkcstgb.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gtzzqystqy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gtfbfwrtio.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gtcrwfkqgi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtpkluceqs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjfqourqe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtpoigvubo.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthqoihxlz.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtguvqilvh.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtqqdaxeqk.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gtgpwkpigu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gthlzkczet.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtbjtmafvy.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtgqlygesx.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gtpktekder.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtldjdrndn.html

[T05] Kotlin：when 表达式
来源：http://dali.zycfv.cn/Article/details/gtygbkhmvp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gtbhmffnli.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtfrzrhsxj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258888.top/Article/details/gtsbghgrkw.html


<!-- 参考信息 -->