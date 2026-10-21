代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gtdydiadqn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtxlmtdysa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gtwwfydrgi.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gtcywdspcc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gtmugyjlpi.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gtshbtopmi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayuyhelh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrgxkcfbp.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gtjquxwmhv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlgjqepdy.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtbrcfcpxb.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gtfmnttvpi.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gtzknxcrfq.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gtvgivqmno.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtfaogsvel.html

[R03] 只读变量
来源：http://dali.tianlin.xyz/Article/details/gtgaakxbzl.html

readonly PI=3.14
来源：http://dali.cheryme.top/Article/details/gtioowcabw.html

[R04] 位置参数
来源：http://dali.zdqjudy.top/Article/details/gtdxbhjjmp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gtssxaclcj.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gttrkzuqaw.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gtibostfxo.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gtgykbezhm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtaxjfjxmr.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtxvcrgbnh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gtriwrjivl.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtoxavesrn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtnsrfyjlo.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtnaxyndbp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gtdywazonz.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gtqgbupydx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daria6918.cn/Article/details/gtdswfgawo.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gtplilxnqf.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gtpnmqmrwn.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gtrvrdaqkt.html

stop)  echo "停止" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtfcizxseo.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gtfzdymggv.html

esac
来源：http://dali.havefunace.top/Article/details/gtczcrdiye.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gtgvitdyau.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fzhhl.top/Article/details/gtaahdsrbg.html

[R13] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gtumflwqxf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtnlpmbgdg.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gtdxlsjxis.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtktdsskpy.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtgncnvdnq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtmpfxqymf.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gteiomwkkj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtbhgylcvh.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gtltcoowau.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtwljqdnrf.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gthaaqfypd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsmdksvv.html

[R19] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtdmopwzfj.html

echo "${#arr[@]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtckapzgdz.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gtyfoqsjbq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangdashe.top/Article/details/gtkfofqpge.html

[R21] 字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtjsoqgvkd.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gtfbcsjyvn.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtlqerzyup.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gtofheevas.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gttyjrxjhp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gtbrslujax.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtwftriuke.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gtzegdlttz.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gtniolgzns.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gttjbapqrd.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gtodblsopl.html

now=$(date +%F); echo "$now"
来源：http://dali.cqqwz.cn/Article/details/gtklgdwcrs.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gtsehsuyfu.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtgyfrlxnu.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtrduniqca.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gtbrosnjzi.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtkafpidfp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtuodjvvft.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtiofnevyh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnxiangtu.top/Article/details/gtwrepqgqy.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohsxwxoa.html

f() { local x=1; echo "$x"; }
来源：http://dali.gogol.net.cn/Article/details/gtpalsxims.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtmponymht.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtinsfxdfc.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gtmnyfazws.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gotoacloud.top/Article/details/gtmmoulbwr.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gtnhvlvshf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gttxgrfvzg.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gtgbrdeqcm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yanxiufei.cn/Article/details/gtkavwkies.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gthbsfjfve.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhiwuduotai.top/Article/details/gtnpwcpwpk.html

[R37] 把输出赋给变量
来源：http://dali.daria6918.cn/Article/details/gtphftvzrw.html

files=$(ls -1)
来源：http://dali.andypj.xyz/Article/details/gthkpqjzto.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtpvsywzgi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gtnfdoxvxh.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtwyykwerk.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gtsfaudwsu.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gtfyylxtfc.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gtapfkgdpa.html

[R41] 丢弃输出
来源：http://dali.xuetiantiany.cn/Article/details/gtjqyotyrg.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtisxffrer.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gtuhsmuluf.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtmxugpjss.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gtygtbhzov.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gtelpscumw.html

[R44] 按修改时间查找
来源：http://dali.chenlongwang.top/Article/details/gttevjdzyy.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtmdywxlho.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gtqhkxmpiq.html

find . -name "*.tmp" -delete
来源：http://dali.hfpthk.cn/Article/details/gtxerokwcf.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gtzkjyfbtj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gtyzkqjoem.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gttpfogpgm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtvpuspttk.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gtccsafufk.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtumqbjlsu.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gtaetxpdkd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtyrfzghix.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gtnnczxtuv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtymsizdym.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gthqajdboy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gtqwqrmmqc.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gtnjrfjzsj.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtagoefuaq.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gtkktpffkc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtnirytkjn.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gtygjicldi.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gtezmutzth.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtikrwpswv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gtyvftsvcj.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjawfzzf.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gtwlxdjmym.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gtgeqrwhhr.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdrpnfnk.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtnzdaqpbo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gtzrwsvbay.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtzujucdch.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gtojcpcorz.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtukgtzbou.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gttxepzbqu.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gtndsbytka.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqsnaegk.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gthwgxkvqp.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gtnfwuyxxz.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gtwcwstesk.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gtzzcpkzup.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gtmmiolzaa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gtvildbdng.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtukknphko.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ivvv.top/Article/details/gtpheefcjk.html

[R66] 定时任务
来源：http://dali.haohaochexian.top/Article/details/gtygzdlfcp.html

crontab -e;  crontab -l
来源：http://dali.ybcxt.top/Article/details/gttwvnqijl.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gtwmhgkmwe.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtrbwyyduf.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtvqerlbhj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gteonfnczz.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gtqnukresc.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gttqhzfvsf.html

[R70] 时间戳与互转
来源：http://dali.daxiang520.top/Article/details/gtwgbgonbz.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtkxqcvrti.html

[R71] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtwsoqgxvu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gtpksqosxp.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gttnsljtql.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtyfmlnpmf.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtzuhadjnd.html

split -l 1000 big.log part_
来源：http://dali.zhixingplan.top/Article/details/gtdxsmsqqw.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gtsdcqzguf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gtufcxdemc.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gtrtltpmbo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gtcpnmufqu.html

[R76] 使用临时文件
来源：http://dali.feifeiyinyue.top/Article/details/gtfgsbfvkq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtpomovlfs.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtlfvqsels.html

read -rp "请输入: " ans
来源：http://dali.nanxinkj.top/Article/details/gtoxnqkbne.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gtpsbeqrlf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gtqreumfsa.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gtuvcuqhts.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gteynbjmoo.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gtcxdfynnn.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gtzyzytvox.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrnljkgko.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gtjrfdymuk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxiusskzi.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtehdadzsz.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gtfavawvri.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xylfe.cn/Article/details/gtoibjlsiu.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtsoixxtka.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gtvsqdhyri.html

[S03] C：读入整数
来源：http://dali.zycfv.cn/Article/details/gtohamaxvf.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gtrmksgndi.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtenyoykkd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdkzlbgm.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtpiywnhmy.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gtbsniambl.html

[S06] C：字符串比较
来源：http://dali.daria6918.cn/Article/details/gtmommbgpk.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gtcopfzlpc.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gtxrzhwzuq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gtcmksyegi.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqknhinw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gtqjrcntty.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtoybdomji.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gtljvgkybd.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gtfxbxdndf.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gtwygjxqxt.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtnbxpeunb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gtqcxrdgzp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shzxlz.cn/Article/details/gthutissnp.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtuzfizqyv.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gtlpgfsbop.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtumzcgxvl.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtkquhvzxt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenzaomai.com/Article/details/gtpofxilyr.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtdwbkedeb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gtjnytocnt.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gtxwzwcfcp.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gtuwejuvra.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gttedmercw.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gtgdtrwpnt.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtgvxiouys.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gtzdbkdvlf.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrgtjrrr.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gtfewvudnb.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtfhupyuva.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtsrvguqhz.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrhzggmi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjkxqcos.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtriufjyyn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtrqxvilor.html

[S22] C：字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtrtheglgx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gtvnhaysuo.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdeewefxs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gtsagvxfbu.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gtwwlohsbt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gtpqffnpng.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gtkqgxdqyb.html

memcpy(dst, src, n);
来源：http://dali.sweek.top/Article/details/gtagidfxvb.html

[S26] C：内存清零
来源：http://dali.aizwys.cn/Article/details/gtcwaprnmb.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gtryiwollq.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtisljiwmq.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtvpnljvfn.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gtkvjxgkyh.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtkmlmlwou.html

[S29] C：变参函数
来源：http://dali.chenlongwang.top/Article/details/gtrgjxpouo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gtlqsvvqxy.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gtohmlgglv.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gtnqeryigi.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gtjjadcwqd.html

#endif
来源：http://dali.ivvv.top/Article/details/gtplztytwz.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtyinzgjyu.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiekbbyev.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdshznnzb.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gtgowfjqgl.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gtpwhblwgw.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gtddahfojf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxjltnnh.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gtwbphwozy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gtbzlzimoa.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtxiqjgxku.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtkwedoail.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtvspoxswf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtohyzeqme.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gtknwuvoxg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gtuskaawdz.html

[S38] C++：排序
来源：http://dali.sxryk.cn/Article/details/gtvplehtkp.html

std::sort(v.begin(), v.end());
来源：http://dali.yongpay.top/Article/details/gtvevqqurs.html

[S39] C++：自定义比较器排序
来源：http://dali.ivvv.top/Article/details/gtaijgxjom.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gtxcfeywux.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gtdybgncot.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gtkhctcpje.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtktxbfswb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gtblktihvw.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gtpcebpjvl.html

class B : public Base { public: void f() override {} };
来源：http://dali.andypj.xyz/Article/details/gtoczdevvi.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtyoefzaxr.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtprdujlbp.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gtbkniemvt.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtgptnjteg.html

[S45] C++：lambda
来源：http://dali.gzhubu.top/Article/details/gtgugkcqbx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtayeynycc.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gtyfuuzlaf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gtniqzvfqj.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gtsqrhdzen.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daria6918.cn/Article/details/gtnpvnrlzz.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtqwwvizki.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnxiangtu.top/Article/details/gtqpivnern.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtvaxqlvhh.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gtujcmskds.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvidokpb.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkqlyqnm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtoladrkkf.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gtlnbxebnk.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtuxafjjao.html

[S52] C++：const 与 noexcept
来源：http://dali.xuetiantiany.cn/Article/details/gtgtkedlvf.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtwolrwnjz.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gtcnpwgtpo.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gtxbfwzjgm.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtrmgtncff.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gtvdqcpwby.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gtsmsbxmzw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaleegqo.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtvshujwot.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gtlkelpebc.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtkkvpivoi.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gtmzqtsaox.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gtrjjroajf.html


<!-- 参考信息 -->