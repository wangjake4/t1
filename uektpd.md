代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtpnmcgtps.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gtfbnekwox.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtruwkafqw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnqzqdqgn.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gtkwpomeqm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwaiwdjev.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gtmnsjkzln.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtlzjsefvf.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gtjlhvgirf.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gtovnaurxe.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gtbavcoxcj.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gtaqrejhpe.html

readonly PI=3.14
来源：http://dali.snrcjt.cn/Article/details/gtogaujxzs.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gtzqtwvkqc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guowangkeji.top/Article/details/gthknvhaxc.html

[R05] 参数默认值
来源：http://dali.9152youxi.cn/Article/details/gtcrskhwef.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gtkjpftehg.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gtwohcabpm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtaypqpniz.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtuyuosxpq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtfgvqkwcq.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gtiwekquyw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gtyrmyozud.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgzqfpsl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gthkiwbyeq.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtgsttvjoq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gttsydkjgo.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gtmvaxxzfd.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gtnappsujp.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gtnxzwrmvf.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtclgnbbsl.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gtrywiceyt.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gtvrswzlqt.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtqfymqtdd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gtgokxkwxx.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtmmvhskyk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gttgqaotqb.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gttdqykwvy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtogadrfbx.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gttbxsphpw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gtnqpkozdh.html

[R16] until 等待条件
来源：http://dali.yvedp.cn/Article/details/gtrryoqtmg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvtcuhee.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gtgvelbjlo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtssgsklre.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gtiayvzpai.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gtpgwsnckc.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtjsbkhgzi.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtzpmlajfo.html

[R20] 关联数组（字典）
来源：http://dali.gaohongyu789.top/Article/details/gtrppekmhk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtzjkkakwj.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtqnzrrrow.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gtdfvsrbmo.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtuhvpnaff.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtkecbyhyx.html

[R23] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtqhbcmssq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcojqppjt.html

[R24] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtzpcbrdrh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gtothkqoot.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gtikmyfcde.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guowangkeji.top/Article/details/gtsfiwczhh.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gtobieespk.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtrsddaktt.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtgewlsdkv.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtzsmacclb.html

[R28] 浮点运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfubpnfq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gtcbsatmdq.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtsmlipmou.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcuihskm.html

[R30] 函数返回状态码
来源：http://dali.xylfe.cn/Article/details/gtzsopamqh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gtguqkrkgj.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtqiqkbndz.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gtlhugoymg.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gtdrkmnojc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjiuxppu.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gtglfrrcgf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gthybobtlw.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtndgqksfg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtyxhqbzsc.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gtzoeujetx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gtnilyzpjg.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gtxtaejpec.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtchajuutt.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtzppjtiku.html

files=$(ls -1)
来源：http://dali.chenlongwang.top/Article/details/gtxpltksdh.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gtrxljfmqw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gtfopavzba.html

[R39] 重定向标准输出与错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtzdorjk.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtspqmivtz.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtoltojuet.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gtzfkctqgb.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gtbanxfkyd.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtiobdknrg.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gtktoezrll.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtfjsruxsi.html

[R43] 按名字查找文件
来源：http://dali.sweek.top/Article/details/gtkwdxtvif.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gtjobvjftw.html

[R44] 按修改时间查找
来源：http://dali.xylfe.cn/Article/details/gtxlgkyrxm.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtzyjulcew.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gtdnrnpbef.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gthibmttda.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gthowfwriv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gthjftzces.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gtlulmhwri.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gtvhwhsvyo.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gtimrukfce.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtuxhflykx.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksachoqh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gtqdkgcnvt.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gtqkjasqur.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtevkklwmi.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gtaacjurdu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gtpjcwptxh.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gtxyffcwnr.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtldlhoemy.html

[R53] 查看文件头与实时尾
来源：http://dali.guannengcc.top/Article/details/gtqwwxvfke.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtvjmecfpw.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gtuuslkrtb.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gtfgevnkxd.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gtngyvfpgy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gtmkcafojq.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtnthwuskg.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gtkammclxj.html

[R57] 远程执行命令
来源：http://dali.yuxming.cn/Article/details/gtsbdsnfcw.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gtfpanqeou.html

[R58] 下载文件
来源：http://dali.wangshuangyany.cn/Article/details/gtcyekklgt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtpyddowae.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtigkvljou.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fzhhl.top/Article/details/gtbodmucuv.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtexasffcg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gtfcvaykso.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gtbsifsnfz.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gtxybolylq.html

[R62] 找最占空间的文件
来源：http://dali.quarkkingdee.top/Article/details/gtaazkwhnz.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtfdyssgrh.html

[R63] 内存与进程
来源：http://dali.c1oappe.top/Article/details/gtaojhfhfj.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gtxgmfzhho.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtueutostg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gtnvhcsgdc.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtjbizkiuh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gtahwkvwup.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtqbbnrhah.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gtwupepuon.html

[R67] 生成随机十六进制串
来源：http://dali.ybcxt.top/Article/details/gtqrrxmhcq.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gtvhndensg.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gtqhpcojwj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gtsqiuwgfc.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gtjryqatfd.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtqkevojwn.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gtajdsatyy.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtklfcizzi.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gtivparcev.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gtezdxypzx.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gtzafblomf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtjhcetfsw.html

[R73] 分割大日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtrekujkto.html

split -l 1000 big.log part_
来源：http://dali.yangfankeji.com/Article/details/gtcgmdtmxy.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gtregfclld.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gtcofeqqsf.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtxpbfzhpx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gtgvqqkzuk.html

[R76] 使用临时文件
来源：http://dali.zhixingplan.top/Article/details/gtbvwennpc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtroqirilv.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gtojgtjuyq.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtnsspxqfn.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gtffnjhqqx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guowangkeji.top/Article/details/gtrjoznpqy.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gteozlslza.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gtjdgqwsuh.html

[R80] 查看脚本执行耗时
来源：http://dali.iojbl.cn/Article/details/gtbxiejfxw.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtjvvxizck.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqnbgcctq.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gttkxfyltg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbjmlnhgt.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtnmdtpgxd.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gtxevmsacp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gtqygnpqhv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gttivcvsnh.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gtlktevvat.html

[S03] C：读入整数
来源：http://dali.ivvv.top/Article/details/gtyrjcfqxi.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtrttmlevu.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gtlvskfkgd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtbpirzgsu.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gtftiiklgl.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gttzockdvj.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtefbqqrmi.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gtbyejanun.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gtorngiima.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtvpysptfs.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gthsymsbrj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gtgasiwvkb.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gtosftoxqb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gtrwwibuik.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gtgrmlysvh.html

int *p = &a;  *p = 5;
来源：http://dali.cqqwz.cn/Article/details/gtvlwhdnnv.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtxterrzfx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gthrbibxaz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gttjaeohdb.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtqjhlnrig.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gtcfwckwtv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttttazryr.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gtmcdjicqs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtrwpnsvvi.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gtzuftgoex.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gtsfepntwv.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gtxawkzvrj.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtggenpqmu.html

[S16] C：位操作置位
来源：http://dali.yongpay.top/Article/details/gttcojhycs.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpdpenou.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gtkodcnxhv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gtrfxryace.html

[S18] C：命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtcqkujfjg.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gtuvccwzue.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gttqaxubvb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlfdxnys.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gtammvsauu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gttutglkoh.html

[S21] C：字符类别判断
来源：http://dali.iojbl.cn/Article/details/gtrjqjrlrg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fzhhl.top/Article/details/gttelwxmfq.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gtwbossrcl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gtbezbhvea.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtsaoknrwy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gtauwoafni.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtrismaeis.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gtpredgesr.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gttbzlubhk.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtvxqofwba.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gtxhptautn.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gtksqsoexm.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtuvdlojtl.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtrubiofvf.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gtvtvehegr.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gtmbbydffo.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gtgfrbompp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtutecnank.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gtjkbxprbz.html

#ifndef X_H
来源：http://dali.hammf.cn/Article/details/gtpvibfawm.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gtqsszpsjs.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtwgqloxpu.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtqutbpoub.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gtvpcmkqso.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtzvocyo.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gtwwivvwbx.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gtwgwefpdb.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtklmiojvw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkrlnsyz.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtqeztmudm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gtjnvofwot.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gtyjtuskiz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtqhcqaljq.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gtzcufkkir.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtxqsnddvo.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtpeocegqx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwsmfjih.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gtcsbqjfsk.html

std::sort(v.begin(), v.end());
来源：http://dali.yongpay.top/Article/details/gtswgmwzjt.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gtaqatkvba.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtlftkwhns.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gtnqxkjqqj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tianlin.xyz/Article/details/gtncxljvnh.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyhqlaon.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gtuuptitvr.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gtbdiiutfa.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gtxxnoftfx.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtduzjfqej.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gthoxtplsk.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gtqexnqxca.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvfwpims.html

[S45] C++：lambda
来源：http://dali.smart0.xyz/Article/details/gtheixcxpe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtuuqclavl.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gtsfkatkuv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gtwffhcedz.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtdtqjrjxc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gtjpozaqpg.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gttpmvntmq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtokcdwymw.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdebycoav.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtizuzmrzp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gtzesznnly.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gtqwzsxfie.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtgaybfbpm.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtwgnupbdf.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gtfgnnmqiy.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gtupqsjwor.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtgsgxhkwa.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gtvwtwxzwj.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsxulgxe.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtapoqpady.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gtcanvgmph.html

[S55] C++：结构化绑定
来源：http://dali.zycfv.cn/Article/details/gtkgzgncdy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gzhubu.top/Article/details/gtccxejldo.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gtiryhmaro.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gtdgqjdbxl.html

[S57] C++：编译期常量
来源：http://dali.jqgufenzy.top/Article/details/gtyuohfjyf.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gtaltoulxe.html

[S58] C++：命名空间
来源：http://dali.tanke756.top/Article/details/gtnqaiuekc.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gtcffakpoy.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gtydpifcpo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gthpxmiofp.html

[S60] C++：遍历并删除元素
来源：http://dali.ydzc1.top/Article/details/gtdrcjcrwf.html


<!-- 参考信息 -->