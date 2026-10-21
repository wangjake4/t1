代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gtaqxocsjd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtpixpjizs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtdeleoytw.html

[Q89] 判断表是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtkspafvyp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hammf.cn/Article/details/gtfvgcrdnd.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gtwfhmofpd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtglhmqsrs.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcresnkse.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhtgqrjm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmscnmfdm.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gtfzsostya.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtbmeapyur.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtaxffytnn.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gtupxnlxnh.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtwitcibym.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtiafahaxz.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gttehjcmlv.html

[R04] 位置参数
来源：http://dali.wangdashe.top/Article/details/gtszdoeluw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtywmsuvmk.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gtxatpuvjn.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gtkwozrhne.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gtfdixmnrj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkicleiz.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gttftoaamx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtymbevvpq.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtncwtwzyh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gthxjxmtag.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapuabteo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtizglnmni.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gtmlrlktrk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gtmjkazoog.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlsiuije.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gthflqnrjh.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtvlczwzzu.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gtnuedeegs.html

*)     echo "未知命令" ;;
来源：http://dali.c1oappe.top/Article/details/gtefvufrti.html

esac
来源：http://dali.yangfankeji.com/Article/details/gteedbptfg.html

[R12] for 遍历文件
来源：http://dali.yj202588.top/Article/details/gtrlcgmzxi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtpqufdavg.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gtwduqxtqs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtcgdjmbut.html

[R14] C 风格 for
来源：http://dali.kuanghao11.cn/Article/details/gttkpxpcms.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtpyjkjylb.html

[R15] while 逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtdflflgmj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gtcfctwmzx.html

[R16] until 等待条件
来源：http://dali.316326.xyz/Article/details/gtxpxmhylj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gtupvwpzud.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtxkwbftxf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gtnnqsifae.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gtwjqzgfdq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gtjgblnwpm.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtwkeozfzy.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gtsfpsgsrd.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtjvzzbowi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gtzwvhncrl.html

[R21] 字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtbhjssojb.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gtecswrcjo.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtdvqsezqs.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtzgytlccv.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtroukpxbm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gtonbroldo.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtssyavqwa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtsmniazry.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gteddblwew.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gtpkeyuuna.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gtxmehadog.html

now=$(date +%F); echo "$now"
来源：http://dali.hfpthk.cn/Article/details/gtbraupezi.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gtokzxppkt.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gttaxfiklh.html

[R28] 浮点运算
来源：http://dali.xziqi.cn/Article/details/gthpabawfu.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gtwblslkxb.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtxonmkmbb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gthrqabcxw.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtseqffyqq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gthqmgzwpb.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtrytrpcuq.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gtdzxvutex.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gtonkvexdl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtbhtyqnky.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gtrnfqinyc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shuidangran.top/Article/details/gtmopnglby.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gtnixqxonq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtobwaupib.html

[R35] 后台执行并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtccsfbsej.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gttfkmcprv.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gtxsuykmth.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszaanlli.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gtjxwujjpe.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtleidumaw.html

[R38] 管道串联
来源：http://dali.gzhubu.top/Article/details/gtoirssoea.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gtsrawkdtg.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtrwaptjvg.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtysfzjexn.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gteiozcjnx.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gtjmujjtbb.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtzpevldun.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdtnlmsu.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gtclauxgju.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtypvnrcdt.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gtnmioigqf.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtlalyqwej.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtvwjvjacd.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gtipqivtth.html

[R45] 批量删除
来源：http://dali.yuanzhike.top/Article/details/gtvgsanyov.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gtdwokpnvz.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gtlgtpaiop.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtiainlfhw.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gtcarkwwhh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtunrrxfrk.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gtlhzjjqtp.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtsajcdydb.html

[R49] awk 带条件
来源：http://dali.daria6918.cn/Article/details/gtzxwfjyem.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtwywwepgf.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gtyctlelyp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvjarylu.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtdiruxbbw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtcdpoboom.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gtkdmrkemv.html

wc -l a.txt
来源：http://dali.jinqigufen.top/Article/details/gtlgdrchnb.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gtaqcspjjn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gtexmgtywk.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtqvvqiffn.html

diff a.txt b.txt
来源：http://dali.nanxuanxn.top/Article/details/gtrzgjwqdo.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gtiwhtqafc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yangfankeji.com/Article/details/gtdifcoeuj.html

[R56] 远程拷贝
来源：http://dali.vqdsnc.cn/Article/details/gttqaumony.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gtdncbvyya.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gthqciuwpv.html

ssh user@host 'uptime'
来源：http://dali.guannengcc.top/Article/details/gtmlsqzatw.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gtutgbndqw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gtnwkjheja.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gtdmznnhbb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gthiikezbq.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtnlgklwie.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gtvtxtydek.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gtwyipcsvm.html

df -h;  du -sh *
来源：http://dali.sysykeji.top/Article/details/gtfzyyvibx.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gtvmbfbbaf.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gtebphydle.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtebmlgzmo.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gtdajspfyf.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gteivtgaqt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gtlsiokzym.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtksqwjhlv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbqcpooq.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gttvzyowhw.html

crontab -e;  crontab -l
来源：http://dali.fengsongda.top/Article/details/gtmcddstqw.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gtsvohnkot.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gtugygubxu.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gtxzsmvvij.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gtcynebmus.html

[R69] 生成随机密码
来源：http://dali.gzhubu.top/Article/details/gtxffssvru.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtrjfggrfn.html

[R70] 时间戳与互转
来源：http://dali.gogol.net.cn/Article/details/gtpomtyxnk.html

date +%s;  date -d @1700000000
来源：http://dali.svipenyu.cn/Article/details/gtnytkxnke.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gthojitafo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gthamjwrys.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsmwupjr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gthlsbskgt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtnzvpbret.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gtudvzcgld.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtnuwptpil.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtjxyobtfb.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtqfhqjbdw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtavqtxmev.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtgcbwhbzq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtnfycvgcd.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gtsxgxbxkf.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gtyprpuqgk.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gttdhigisy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gtjtypcjng.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykecwaaf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gtgekaeuvm.html

[R80] 查看脚本执行耗时
来源：http://dali.shuidangran.top/Article/details/gtfgizoycm.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gtkjxcqrbe.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtguvtxrgz.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gtmlvwqqkm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvmbaeqer.html

[S01] C：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtzclzthcp.html

#include <stdio.h>
来源：http://dali.pycfn.com/Article/details/gtomhbewqo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtbzypwpul.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtkupzgutj.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gtsxlckzpk.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gtafrzvotq.html

int x; scanf("%d", &x);
来源：http://dali.jinqigufen.top/Article/details/gtqotopmby.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcgvpkpg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gtpdwjhgmz.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gtblskitxo.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gtxozmgkcb.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gtnjxwrggm.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gtmvnpntrw.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gtsaqgimli.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gtxddbbior.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtsnkjzbrz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gtaoafmqju.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gtnvwpqqck.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gtmrvqtxim.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gtcegiekgr.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gtthjdumtg.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtnquymmoc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtjaopvtar.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gthxebysjf.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gteshvcnda.html

[S12] C：写文件
来源：http://dali.zdqjudy.top/Article/details/gtgimxpczb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtrwknwmat.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtxqcxlkzp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jianghu66.top/Article/details/gtecmfnrno.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gtfxrtxteq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gttlhxqcys.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtcpozwgzz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gtzgwcyncw.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gtyptottui.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gtluiuhxkq.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtkuigarag.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gtfwtkfpzi.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gttxcqivgq.html

int main(int argc, char **argv)
来源：http://dali.cashguo.top/Article/details/gtrkkjkwgp.html

[S19] C：快速排序
来源：http://dali.sysykeji.top/Article/details/gtwkdphbsi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gttrhmzhcg.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtrgppeply.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtfwxjtwmt.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gtzpswcngb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gthgvyyomc.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtuprbmrsp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gtzyuqnsba.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtwzulkjly.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gtlktbcqys.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gtlgsvnuox.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gtpjugfgsl.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtcoqqhobu.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtalmbzyif.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gtevlkyhla.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gtbgqkfhdm.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtwpxgoufp.html

const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtgccksrim.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtbrwhvakj.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gtrczwhygg.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gtiuisvoua.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtqtrwpxnv.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gthnmomire.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtedrpycwp.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gtincodsbw.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtfkkvpzsr.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtticxhvix.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtxjmetcze.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gtagkbtgbx.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gtgerhqmme.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gtbtomhunk.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gtakawxaiq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gtaffcdrid.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gtvyxmpdja.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gtwiwlacox.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gtocxgpuil.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtvwpuwfba.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gtkaxvirhx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtpxruomhp.html

[S37] C++：set
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuhsreha.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtlftctvsi.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gtcogouxln.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtspdtuqry.html

[S39] C++：自定义比较器排序
来源：http://dali.ivvv.top/Article/details/gttxmakyjw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gtukdfetzs.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gtfofyopgm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtpogugncy.html

[S41] C++：类与构造函数
来源：http://dali.tianlin.xyz/Article/details/gtscmbhyrr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtosmjlqgg.html

[S42] C++：继承与虚函数
来源：http://dali.chenjidiqi.icu/Article/details/gtbaibapuh.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gtxqxjqerc.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtfesxaudb.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gtdcceoesa.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gtoebfclxs.html

void inc(int &x) { ++x; }
来源：http://dali.mhx1999.top/Article/details/gthwtvvoss.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtmgoxsuxj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gtjopybrxe.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gthkzvrdbv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtbkpaajjt.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtnnbafdcv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gtkhzmzcsk.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gthtwdhrvo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenzaomai.com/Article/details/gtbhzzilor.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtsrawyoaq.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtzffqjmhl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gtffpleyir.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gtzpxzamki.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtypgwhrfl.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtrfmfvfpm.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtwrtdtgcl.html

[S52] C++：const 与 noexcept
来源：http://dali.vqdsnc.cn/Article/details/gteymlokcj.html

int size() const noexcept { return n_; }
来源：http://dali.jyoumei.cn/Article/details/gtshsehlrz.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtwgyoztci.html

std::vector<int> w = std::move(v);
来源：http://dali.svipenyu.cn/Article/details/gtefgihnla.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtbnhvvrnh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gtmozlxlpe.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gttjngmfmz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gtgjskpkxz.html

[S56] C++：optional
来源：http://dali.sweek.top/Article/details/gtsrutjhvz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gttxtyuzuy.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtyqcbtbwj.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtsnsyegvn.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gttifafjwc.html


<!-- 参考信息 -->