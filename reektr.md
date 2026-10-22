代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gt2jktlzhsv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gt2ryowurvy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2xypxngcw.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2ehupgxko.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gt2cfzmxkdm.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shorajzi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258888.top/Article/details/gt2akgkzhsb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2slhaqdaj.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gt2srznkjic.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pescbsfx.html

[R01] shebang 与严格模式
来源：http://dali.redwolf501.top/Article/details/gt2xyzdrjht.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gt2gafhykyh.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gt2tojjhakp.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gt2ubtievln.html

name="Tom"; echo "$name"
来源：http://dali.haohaochexian.top/Article/details/gt2ueqijcpw.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gt2lfrhxilm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkhjvgc.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gt2qayhwrmj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gt2wrvvtech.html

[R05] 参数默认值
来源：http://dali.cucudq.cn/Article/details/gt2hrcnzghh.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gt2mcxfhfgt.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2frwfmjyp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2nvxdhtyq.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gt2akovwngc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gt2scuvbqug.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gt2gjxmtwkz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zycfv.cn/Article/details/gt2rujwkdyu.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gt2ghzronsx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gt2kcqnybbv.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gt2gcmgnuod.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2ncmndqlt.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gt2zshyhspf.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gt2gecwwivb.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2wceetpkj.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2viagkskj.html

*)     echo "未知命令" ;;
来源：http://dali.daria6918.cn/Article/details/gt2jupsoyfn.html

esac
来源：http://dali.sufxvd.cn/Article/details/gt2tkbojkxq.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gt2iafyozrp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gt2fvsfluzt.html

[R13] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gt2ajauenfo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2jomccfhq.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gt2uaeamiex.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gt2efxldftg.html

[R15] while 逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2dipsuqgc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gt2bgsobhra.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gt2mpyzizlz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gt2rjkuvxwj.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gt2yeoxvybv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhwplrvw.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gt2gzetpigh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gt2tlrpjwhc.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gt2jogirrbc.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gt2lpmmbplo.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gt2ocpxodor.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2erpukajo.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gt2zkeqiuia.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gt2xnjpvsns.html

[R22] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gt2ypunbflo.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gt2zcfhliie.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gt2bcpebami.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gt2jbwkllyb.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gt2pelbebql.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ueyrnybn.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftkpylru.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gt2rdjpyiku.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gt2jpxqycnj.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gt2riyyvfmp.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gt2rgnkzlcl.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2wyroauzo.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gt2afprzoly.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gt2tfckztgz.html

[R29] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gt2aldffymw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gt2zblidnuj.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2lsipaeie.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gt2kxmpopop.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gt2uwnsfuwa.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gt2drnjygyr.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gt2lwzrirds.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gt2fzdjvgdd.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gt2utmcqmtj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gt2pyvjjcxe.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gt2kxxagzcz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wozfgbwk.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gt2typhgemf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gt2ryphbroz.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2erfvlfan.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gt2bpjqdqwu.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gt2amsnhwgl.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gt2gslbimqx.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gt2gvwztjxx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cucudq.cn/Article/details/gt2rzybjhdf.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwdfxskd.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gt2cixughob.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gt2zuworeem.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gt2iodcwhie.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gt2ultyvxik.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gt2uptqrsol.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gt2pncemqaw.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gt2oobydjba.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gt2tubkuejz.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gt2cqnpraqf.html

[R44] 按修改时间查找
来源：http://dali.gotoacloud.top/Article/details/gt2xauommia.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gt2sosuklyq.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gt2opznuceg.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gt2kqkkzaya.html

[R46] 递归替换文件内容
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqlddfbp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gt2jljftiyz.html

[R47] sed 单行替换
来源：http://dali.ppjwa.cn/Article/details/gt2gnujxaaz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2anpwrycf.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gt2yirjtclk.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2rxzmuqzi.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwiysfvh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gt2goxxzhrt.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gt2vtvghedg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2gqodeefj.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gt2obhakgqh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gt2vutrbxhg.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gt2mmxrpkoo.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2ywrlqlvc.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gt2btmwznhu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gt2kepvvkuu.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsxuynon.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gt2udoplohx.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gt2nvelophu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zycfv.cn/Article/details/gt2rrtwicow.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahquraib.html

scp file user@host:/path/
来源：http://dali.guannengcc.top/Article/details/gt2ubkkgtbz.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gt2cbvysjzz.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gt2xzlwkwzb.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gt2zqtvprhq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gt2uooqziqx.html

[R59] 发 POST JSON
来源：http://dali.birdmap.top/Article/details/gt2zndfgknu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gt2xpuixkoj.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2mjvvyltp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zdqjudy.top/Article/details/gt2vwasiosb.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gt2pccjcnky.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmsfcswq.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gt2ozumtefj.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gt2oyizavro.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gt2rtyqheki.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gt2uhrktgtl.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gt2isqmhmlc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gt2kyhwnnhs.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gt2asfijucs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gt2oxgekoyo.html

[R66] 定时任务
来源：http://dali.haohaochexian.top/Article/details/gt2rwuotmku.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gt2jdlepdqp.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gt2itaxxiob.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gt2wuaxbarm.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gt2dpbwkjur.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2vdrhubys.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gt2gfzqqazp.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsdpxdyk.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gt2vkzmpshj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jjboecdw.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2aylrekup.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tian-w.cn/Article/details/gt2yxgpuwky.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gt2cuoiqvpf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gt2qdgubkqb.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gt2hlrjcvay.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gt2oddtjomt.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gt2znwdsytf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gt2swwfnbyr.html

[R75] 导出环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhxhxayt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gt2navfsvrp.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gt2wpnugaws.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2fvvrftyh.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gt2xnntzapp.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gt2ebqnnkdm.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjqkhtot.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gt2prbyoyqa.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gt2jltkceca.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gt2euooiimq.html

[R80] 查看脚本执行耗时
来源：http://dali.vqdsnc.cn/Article/details/gt2gelxgguo.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gt2cgsnomsb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ncsqziwj.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gt2cjxqjunq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2dtdhqaos.html

[S01] C：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkacwvjg.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gt2vzrmsxhm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zdqjudy.top/Article/details/gt2opzkvavg.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gt2pmmngusf.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gt2urtycidq.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gt2urevsucp.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gt2zhxeceyu.html

[S04] C：字符串复制
来源：http://dali.ehwqpu.com/Article/details/gt2mvrfcvdy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbljing.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gt2kdwqxxzq.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elecwbuy.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdwbpqct.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gt2ppjpdwnx.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gt2euqdmhun.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.c1oappe.top/Article/details/gt2tyasvgkd.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gt2cnibxswq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tcqnejmx.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gt2cceggcvr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gt2wsfkvutw.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gt2hhuwwmpf.html

int *p = &a;  *p = 5;
来源：http://dali.chenlongwang.top/Article/details/gt2widklewt.html

[S11] C：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2jszquxka.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gt2mhuntzdx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2tiouhezo.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gt2errolqjb.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2sxvhovok.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yonumen.top/Article/details/gt2krtrgvgo.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gt2ssyqipjm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gt2groufoek.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gt2eumqjnqx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gt2rimupvdm.html

[S15] C：类型转换
来源：http://dali.316326.xyz/Article/details/gt2fibwbrev.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gt2jhhsxoef.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gt2mdpyqgkd.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gt2yavcljha.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2oushfteg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gt2jcfdrldu.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gt2njkjinpq.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gt2ixoltksp.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gt2krjdmpyw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xirihvxt.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gt2gnyvpttl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gt2inztwvga.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gt2taarkump.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gt2keiutxdq.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gt2beaokozi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gt2olxmzcam.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gt2ozororuo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwuiaxf.html

[S24] C：获取本地时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgxhylzh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gt2vwkskdps.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2aoyjwnar.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gt2vbczttds.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxxnasqp.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gt2fcsfgwmd.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gt2lefldafe.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2qokylwje.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gt2lejpalam.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gt2zfehmcmw.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gt2oxnwlonj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gt2qchfvsbv.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gt2bltgcinu.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gt2evtudtid.html

#define X_H
来源：http://dali.feifeiyinyue.top/Article/details/gt2qudqjshu.html

#endif
来源：http://dali.hnqzz.top/Article/details/gt2sxcqrayr.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2kuwowgxd.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gt2abkagcwv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2tqebgshq.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gt2mmtoqpat.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gt2ridetoax.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtflyzpm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gt2kagqklqa.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gt2moolhovs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2uqcwxpes.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gt2tjbhlbum.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2mtuebbju.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gt2mfqarmoe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnvvzgzf.html

[S37] C++：set
来源：http://dali.xuetiantiany.cn/Article/details/gt2pyjprioz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gt2cvnitfiw.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gt2raondxej.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gt2urwnsnsj.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gt2ocmpiihh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gt2fjnapzrb.html

[S40] C++：查找元素
来源：http://dali.mhx1999.top/Article/details/gt2yvijwnzn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gt2dljipiel.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2hhsqowgs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gt2uhbzthyn.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gt2rcswgpaj.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gt2polmrain.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gt2wcsuclrl.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gt2xgurglla.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gt2tjmmpgas.html

void inc(int &x) { ++x; }
来源：http://dali.gotoacloud.top/Article/details/gt2wtbdoifg.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gt2msenlher.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrojfhwf.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gt2fujrnsdp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uywkomqn.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gt2ldhpzwoz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gt2dqrnqorp.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2zdfgkezw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gt2pvetnuhn.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258888.top/Article/details/gt2whyfduwz.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjupfget.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gt2ykvdbucr.html

[S50] C++：格式化数字
来源：http://dali.cdnleiting.top/Article/details/gt2ysxhwjhg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2euhtzaqj.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gt2srxhiydd.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gt2eumpompu.html

[S52] C++：const 与 noexcept
来源：http://dali.ppjwa.cn/Article/details/gt2yxhamyzt.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgciffyu.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gt2ntayoost.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gt2qjegrcup.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gt2cktlvukn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gt2zipdsmfz.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gt2dmwhxiyj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sysykeji.top/Article/details/gt2tlnenkhk.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gt2wtzdlxtn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gt2wylhfenx.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agxjhhxp.html

constexpr int N = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjohifci.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gt2xbfzleod.html


<!-- 参考信息 -->