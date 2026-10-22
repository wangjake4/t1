代发 wailian999

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gtmpixewhc.html

[R04] 位置参数
来源：http://dali.hnqzz.top/Article/details/gtqjycgkqu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gtgxsmlrnk.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gtmrnqaiyx.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtyvrxrrrw.html

[R06] 判断命令是否存在
来源：http://dali.cqqwz.cn/Article/details/gtwnbgqziv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtwpwlgdqf.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtbrwwyxcj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtvmnvqkks.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gtthiaauuv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gtseuvjcsz.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtasbfdlzj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gtuyiqnvpz.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtrmyfoqli.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnqzz.top/Article/details/gtaatqmyjf.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gtrphzezal.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtradxnjoi.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjpbrbkr.html

stop)  echo "停止" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtfzlbzjen.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gtzecvuqse.html

esac
来源：http://dali.yj20258.top/Article/details/gtxjffmqte.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gtbmtebagi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajnqiogo.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtztqbponm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtfjrhklmz.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gtzvqvntns.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtmpscdfer.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtesfadexi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gttdnkbssi.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gtzbijeiqh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtngamhapf.html

[R17] 数组定义与取值
来源：http://dali.sufxvd.cn/Article/details/gtsslkcibb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gtvzgbxodw.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gtptjtuhgz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gtweheabby.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtmdvtorct.html

echo "${#arr[@]}"
来源：http://dali.cucudq.cn/Article/details/gtdrxufbmj.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttspiyita.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gtynwixxhx.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtdjytbgzq.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gtjnsbxfpp.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtaqrhtqmt.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gtgflxibkm.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtsrfcaefn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gtgvfgzsaa.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtgqgtjvwe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtlijyoylj.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gtnvfcxzvv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtwitblzez.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gtlwdubgln.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gtusfuflbm.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gtlixtghjy.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtoowyzvcp.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gthcyykqxh.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnhkyqzo.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtxhkirjod.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daxiang520.top/Article/details/gthziduljj.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtnundazcx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gtecplrvyc.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gtddfpytmp.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gtdyikmjlt.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gtsgfljaco.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtqbgkxdxx.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtayumyyia.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gthzvmjelu.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtvslcklfn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtewsweipf.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gtulbxxwfe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gtfflzrghg.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtedpsrgeo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gtcamwyjvv.html

[R37] 把输出赋给变量
来源：http://dali.fzhhl.top/Article/details/gtpuhwioee.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvdrgqyem.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gtqbjpmdpg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gtqqiwzzme.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gtjetzjdws.html

cmd > out.log 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtdartjdmi.html

[R40] 追加写日志
来源：http://dali.hywenlv.cn/Article/details/gtupibjske.html

echo "log" >> out.log
来源：http://dali.cqqwz.cn/Article/details/gtgiviyrmz.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvhvdgal.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gttgxrlvnd.html

[R42] 输入重定向
来源：http://dali.daria6918.cn/Article/details/gtzapvlxhd.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gtydklrcxa.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gtrpvsewog.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtavxavdwn.html

[R44] 按修改时间查找
来源：http://dali.xziqi.cn/Article/details/gtinsttrjf.html

find . -mtime -7 -type f
来源：http://dali.yj20258.top/Article/details/gtoewduvip.html

[R45] 批量删除
来源：http://dali.ivvv.top/Article/details/gtjinhjllx.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gtlrhyfedm.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtctkkdbes.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtklyfmurw.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtajdmjevj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtjexiyjmi.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gtlfxdbwpp.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtyzrnefnh.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtlrfxxprr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuxming.cn/Article/details/gtebzpgcgo.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gtylvuiysa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtvgxdwhvp.html

[R51] 排序去重取前几
来源：http://dali.zhengqikj.top/Article/details/gtkupkuogy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gtbfmkbgpb.html

[R52] 统计行数
来源：http://dali.sufxvd.cn/Article/details/gtytcbydiy.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gtcutnucgw.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtsqcmlwab.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gtulgdscgs.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtwlygoput.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gtsfmsaqgf.html

[R55] 压缩与解压
来源：http://dali.hysaishi.cn/Article/details/gtpqgreiuk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtivowdtjk.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gtrvmvxpau.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gtknujdlsl.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gtkwzflrez.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gtzijcxwho.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanlkefuc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtboceysgy.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtgnhuvmkn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtwklwsoim.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtxnvroogf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gtmtcunjoy.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gtgontwykx.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtxceaywec.html

[R62] 找最占空间的文件
来源：http://dali.yj20258888.top/Article/details/gtodysogqg.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gtkplhoguq.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxghtgbq.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtyncmpaxe.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaktfglf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nwbrower.top/Article/details/gtgpbxzcxv.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gtpexxokvz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gtyawlnakz.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gtioitajsy.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtvbxmgjam.html

[R67] 生成随机十六进制串
来源：http://dali.zhengqikj.top/Article/details/gtnqhjnvjp.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gtozwiwojf.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfohyrxd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gtlfoundwx.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gtcbvuemxg.html

head -c 16 /dev/urandom | base64
来源：http://dali.shuidangran.top/Article/details/gtkddmockm.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gtoydifkwg.html

date +%s;  date -d @1700000000
来源：http://dali.cashguo.top/Article/details/gtmmnvhywi.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtlwyzuaoh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gttdwzpkvc.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gtuavvxlsh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtamjpsliu.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gtwjgpymfs.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gtklhvpcwh.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gtsximzgjp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gtyimdxlao.html

[R75] 导出环境变量
来源：http://dali.hywenlv.cn/Article/details/gtoncbeakb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gtpzllgnlv.html

[R76] 使用临时文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgmqraol.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtfkyhtbud.html

[R77] 读取用户输入
来源：http://dali.jlsjyb.cn/Article/details/gtxvaydtey.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gtdqxqpfyt.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gtxecdonuw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gtfemnizlb.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gtbtjaqlxg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksabuvgp.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gtqsbvvlhn.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gtwhrluqth.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtemvlkxqs.html

S. C / C++ 专题
来源：http://dali.yvedp.cn/Article/details/gtxqazjwyq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjirgyum.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtkqwjkmtl.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gtycusuxri.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtvkegyeka.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtnyrdwmcv.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gtrahpbnqn.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gtoubmqzqb.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtfjwvarvb.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gtqudzyuoh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gthmbhxphl.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtnsehezsa.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gtufperire.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtvzzdgyaw.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gtclkgfgkr.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtzljxaiyq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gtjwzfmjib.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gtzetheqsu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gtzlantnvq.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gtsoluziks.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gtcavdqhtu.html

[S10] C：指针与解引用
来源：http://dali.chenzaomai.com/Article/details/gtuszygrmi.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtgjcrpskv.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtjmrdmdzb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtekcpxdbp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gticgwzkhw.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gtsdatmpuy.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtikwkueoz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtkwlhkakc.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gthzeixxvq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtjvsftomm.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gtrshhmjgy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtzwuvdlrs.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gthafdmlvt.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gtfynybnuw.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gtmxexewrr.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gtnsdqihek.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtvukfdhpm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtvmlqyhro.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtgiqbirxb.html

int main(int argc, char **argv)
来源：http://dali.c1oappe.top/Article/details/gtcpbhtgmu.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gttiwuxuvl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtuymmwypi.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gthkzbskmw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtlenexfet.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdhtahwx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtfgjjvrtb.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtkwgixsgf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gtemjdyhds.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gtupkcvkkx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gtnavhevke.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gttmghswhk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gtnakbytei.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gtrzzvjsoq.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gtttupxmtc.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gtmzlrzyzw.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbgxclnc.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtzlsctgaz.html

const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtlhjfambl.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gtjbryside.html

static int counter = 0;
来源：http://dali.yvedp.cn/Article/details/gtqrhzwver.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtcnncxawn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtxavxjwtq.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gtsmoknsoi.html

#ifndef X_H
来源：http://dali.yj202588.top/Article/details/gttmmyurqy.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtggkqeogx.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gtmbifohfz.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtwupmlzif.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtjwyyhqow.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gtvijiitnp.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gthvpqzjpj.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gtwlkynynb.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gtldzwnfom.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gtkqyltwqe.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gtmozyiemw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gtfjvfppav.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtozoemshm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtfuxcowjv.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gtnhvqldmh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzzcozif.html

[S37] C++：set
来源：http://dali.iojbl.cn/Article/details/gtpjokoigd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gtpqyvwolt.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gtnjsnckmk.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gtkgbdsovp.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gtrujclmgw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gtynvoqcle.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gtnlqcgcnk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtdbyabfwa.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtzkyzrmxo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gtiosscxxl.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gtpogxapbp.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gtjfnasnit.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gtvyxslnfx.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtpegymwlq.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gtvrnjjkxp.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gtejlkspku.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtjietizub.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gtltqbiglp.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gthavqstiw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtjyapxydq.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtrihyucee.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtpyjqjgva.html

[S48] C++：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtuydkukpc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtelsiomkj.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtwduqgvzj.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohazgran.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gtacgcdbeb.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gtinydqkho.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hammf.cn/Article/details/gtaozncahp.html

[S51] C++：显式类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfjvbimp.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gtqerpilei.html

[S52] C++：const 与 noexcept
来源：http://dali.redwolf501.top/Article/details/gtyjsfmqqd.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gtritpnapk.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gtlsnhshaj.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gtrqjgulwu.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gtirbyrjvy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gtoelwpejj.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gtzwmyoxdh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtozzmyjrg.html

[S56] C++：optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzupjqaad.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gtnllrunit.html

[S57] C++：编译期常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjulvbzo.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtsfhzkqnh.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gtpjmzsgdq.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gtjzcioajn.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gtcijyamov.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zycfv.cn/Article/details/gtexzdpxho.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxuanxn.top/Article/details/gtyghjsacl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gtbahugsqv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqpakzmtu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtunyuxngr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqvmgdixc.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtqsdrmwuz.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtnbxboqpp.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gtyntkmfrn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gtecaboavj.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gtatbpsvve.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtsflupirz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gtjgizhtzi.html

val n: String? = null;  n?.length
来源：http://dali.nwbrower.top/Article/details/gtvlyhqzcl.html


<!-- 参考信息 -->