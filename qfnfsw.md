代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.cqqwz.cn/Article/details/gtuftjlomw.html

SELECT TRIM(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtnzhsczmx.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gtxlidmheb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gtuwujrhnb.html

[Q86] 读取 JSON 字段
来源：http://dali.hongshengwenyu.top/Article/details/gttbzzrzex.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gtwheehyru.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gtdvywfkrp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.c1oappe.top/Article/details/gtdprcfrqr.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gtudphyvgo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangshuangyany.cn/Article/details/gtywhotzdp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtibmqixkx.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gtcqkfknbz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtxmbfoaxf.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gtwheggudb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gtoeudosco.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gteumrastw.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gtgixpfblf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnfvwtnq.html

[R01] shebang 与严格模式
来源：http://dali.sweek.top/Article/details/gtskzjloii.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gtbwmiwuxo.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtfjznjhyc.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gtosdbvlyx.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gtbixnmxzc.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gtzursqcjz.html

readonly PI=3.14
来源：http://dali.cucudq.cn/Article/details/gtsmrxwmbs.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtahbkolld.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dianchejie.cn/Article/details/gtldqgtxgy.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtacppqgkw.html

name="${1:-default}"
来源：http://dali.kuanghao11.cn/Article/details/gtjistjyef.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtbdyudcsm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtvoxgoxlg.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gtpnelayje.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtqugrqavf.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gtbjvhnutg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtmfoaymrr.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gttltliyhc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gteqepctqt.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtdtiylbgk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gtpsmvsvnz.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gtounzpqni.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtwjsuovof.html

start) echo "启动" ;;
来源：http://dali.cdnleiting.top/Article/details/gtexigzlep.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gtqypxmbrn.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gtegdmwzlp.html

esac
来源：http://dali.xylfe.cn/Article/details/gteuwvwbkn.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtudbbavei.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gtumvderjh.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgccjpjz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtjolkxqiy.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gtqzwkcnof.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gtnfikhvhc.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtziqpiuhk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gtfvhlggxk.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gtjvjypeve.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtfilldqxl.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtuybfchlo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gtlwtaxxay.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtficwpoax.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtvfbflagg.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gttyzzsuxg.html

echo "${#arr[@]}"
来源：http://dali.cqqwz.cn/Article/details/gtlqogekce.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqecxhlwp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gtuhhnjwka.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtbncilbfs.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gttztpugcw.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtdlcgidaz.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gtmatjblsm.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtdettqalm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gtpcxwijqz.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtleawganl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtjmhxiwjj.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gtrahvrfsg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gtmzmbfndx.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gtimvlegxm.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gttsrjquwe.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gtjuwhuoqs.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnzvuvlr.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gtidvnbnbn.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtbydhqijt.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gtggbgvkun.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gtilxfkewn.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtslomksfa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yangfankeji.com/Article/details/gtoquzculi.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gtijuahivv.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gtlszzdawj.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gtrilhkrzw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gtqfaossjy.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gtvuqpjluz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gthimfmhzu.html

[R34] 退出时清理
来源：http://dali.zhiwuduotai.top/Article/details/gtpnnqgvtg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtnsjshwnc.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gtawcrbtbf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjsvyhxq.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdzpjzfn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gtaqorlzto.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gtbqjpvgjs.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gtfscvfuci.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gtgdpbyjxe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gtwczaiznj.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gtozhtdhqg.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gtmckqvwqu.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gtdplxbawp.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gtjqxxapar.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gtkhjbamev.html

cmd >/dev/null 2>&1
来源：http://dali.yvedp.cn/Article/details/gtocdiioou.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gtolcaydgn.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gtkkjtbdud.html

[R43] 按名字查找文件
来源：http://dali.yueranfly.top/Article/details/gtopgwxjlg.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gtrxnjfbbc.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gthntwlkby.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gtrcqpehes.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gtjlghklkh.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gtsynezjhh.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gtkvjexxvg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gtzdjxwdrc.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gtqqbsvoxo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gthhgrgmko.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gtsnlpuxzj.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gtpjjlyoqx.html

[R49] awk 带条件
来源：http://dali.fengsongda.top/Article/details/gtbzvzkdci.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gtetxoenwe.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gttffbymae.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtpzizrlaj.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gtaevkvpug.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ydzc1.top/Article/details/gtacolcptz.html

[R52] 统计行数
来源：http://dali.yj202588.top/Article/details/gtcputcwal.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gtcbjjyafh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhoulong.xyz/Article/details/gtwhmnmivo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtxnryfixu.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtgnqdazhs.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtlqayxlbl.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gtonocqtge.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gtkpbyasuj.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtjdqcdsdp.html

scp file user@host:/path/
来源：http://dali.dashuyun.cn/Article/details/gtwnafidaz.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gtehwfeesz.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gtmvvnejku.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtufjbyrrz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtymfrpjqz.html

[R59] 发 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtouwmnqqn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gtargmoung.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtrquoqxhk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtzusvmpry.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gtvqjdkmbb.html

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gtafiarfpv.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtrrialbnv.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtuousxoya.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gtlwfcmbus.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gtfqisfezc.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gtunzneqso.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gtaibhmsoo.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gtzsvczeca.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtcafqntkg.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtbayazxeo.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gtelhjlhkb.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gtsggceqnl.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gtwicxxsez.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gtzwkpxtqs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fzhhl.top/Article/details/gtiofuamng.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gtobdrdvuj.html

head -c 16 /dev/urandom | base64
来源：http://dali.guowangkeji.top/Article/details/gtjyhbrbzt.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gtkbxlkhat.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtntawcxhu.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtciobclfc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.316326.xyz/Article/details/gtxpueixib.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gtyxsadwgi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtneniustk.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gtgjanbhko.html

split -l 1000 big.log part_
来源：http://dali.quarkkingdee.top/Article/details/gtfjsbpksq.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gthnkfutfa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gtgnbyimck.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gtekeipbkn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gttceelfxj.html

[R76] 使用临时文件
来源：http://dali.ehwqpu.com/Article/details/gtvzgugfmh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtzkwsjjid.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtkyyageve.html

read -rp "请输入: " ans
来源：http://dali.sweek.top/Article/details/gtxvhybqvt.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gthkywtjda.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gtyjjhojsa.html

[R79] 解析命令行选项
来源：http://dali.c1oappe.top/Article/details/gtbhaijwrv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jiagoushi.top/Article/details/gtxgcmzpaj.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gtnaoquaoy.html

time ./run.sh
来源：http://dali.jyoumei.cn/Article/details/gtqwxlkrhe.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtchtwkund.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtceomjjcy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvkegroam.html

[S01] C：Hello World
来源：http://dali.xylfe.cn/Article/details/gtdujoulqk.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtjbbumxng.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gttfevqwnh.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtfxrsgsbj.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtesvfbofw.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gtvpgayojl.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gtsegbzjtc.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gtkchhpsqn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtfafjlpza.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtjggqdmwe.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gtontfbwio.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gtztxbbizu.html

strcmp(a, b) == 0
来源：http://dali.feifeiyinyue.top/Article/details/gtupqdqzjb.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gtxjnimqzq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gtnyaezotk.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gtqjihdpci.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gzhubu.top/Article/details/gtvkdlzfsp.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gtlaluqsbu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guannengcc.top/Article/details/gtonvtllmf.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gttyalolcb.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gtygqimhjv.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtjonfyrsc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtjuphctna.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtaqcshvuc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtawlitjdk.html

[S12] C：写文件
来源：http://dali.zdqjudy.top/Article/details/gttqcijcfk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gtcvdyosce.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtwqwoczcg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwtcoqwc.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtvrvxziyj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daxiang520.top/Article/details/gtoqsakeld.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gtuxsyjdfh.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gtbmiykrac.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtfzhqxefy.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gtugzfgcsr.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtnrwxyhzs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gtpfpguwrt.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtyrbwhuft.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gtbnczbyqm.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtqboygyfo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtivmfynyq.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gthhplnllx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtsintluwk.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gtixhkryzp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtvgzjmlnh.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtnulzsork.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gtplnencsm.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gtkkvyseiv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yueranfly.top/Article/details/gtxzibcrqi.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gtjlofroza.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gtpcuchcvi.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gtmednabho.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbepfovae.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gthtaqavyi.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gtskdaagln.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtbpxeqbbj.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gttgipmfou.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gtalgqiven.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gtvosutvly.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gtmjiovvcv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gtyfbagmln.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxqdzfvh.html

#ifndef X_H
来源：http://dali.zhoulong.xyz/Article/details/gtxuesiguv.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtscsxxvus.html

#endif
来源：http://dali.xuanzx.com/Article/details/gtgzwmvviz.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gtxmwfhscx.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gtjdxjvirw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnwqaldk.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gtwpayudjm.html

std::string s = "hi";  s += "!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiiibdohg.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gtwvaqsgzy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtrukuvvpe.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrqzbmai.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwdnamhpq.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gtzffprbnj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtbozzbkze.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtixdtaalj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtkmwxvwfb.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gtnwjmpdkd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gtcdqqillp.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gtgpwopotq.html

std::sort(v.begin(), v.end());
来源：http://dali.nwbrower.top/Article/details/gtwqsudfio.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gtkhbfczea.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtgkhlkeov.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gtfekqnrdf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gtpzyyrbof.html

[S41] C++：类与构造函数
来源：http://dali.dianchejie.cn/Article/details/gtaclmohnh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnacarqep.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gtqojlwfty.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gtzggvmeob.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gtiitukaeg.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gttfkasqge.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gtzkpvkeoo.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtlihtfwte.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gtaimiyixw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznczqtqw.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gtpjwfnqil.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgrvurwyq.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gtvbpdnaiu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtijbhfvbc.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtlracvxbq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gtsvfiuydi.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gteskwmahq.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtakwgrxwc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gttayjcvot.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsixjjphg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtczzaftxj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gthrozhjrr.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gtbwuqhzys.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gtlsiheqpb.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtozlfdvhl.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtoupxebqw.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gtutahbugo.html

[S54] C++：异常处理
来源：http://dali.hysaishi.cn/Article/details/gtnsdtrczj.html


<!-- 参考信息 -->