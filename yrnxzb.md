代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.yangfankeji.com/Article/details/gtcrnpnyit.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtkeininwr.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtwciruzpb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtjlkbkrie.html

[Q84] 去除首尾空格
来源：http://dali.chenzaomai.com/Article/details/gtvvojfefk.html

SELECT TRIM(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtppgumdry.html

[Q85] 数值取整
来源：http://dali.jqgufenzy.top/Article/details/gtttthppzh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gtyjtharqo.html

[Q86] 读取 JSON 字段
来源：http://dali.yanxiufei.cn/Article/details/gteihrwulr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gtzsdyscdx.html

[Q87] JSON 字段做条件
来源：http://dali.zhengqikj.top/Article/details/gtwrhzwkfr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtkxijrntk.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gthzkfjabj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gtbqtjhpva.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtzyquywmt.html

[Q89] 判断表是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtqoxkznue.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtvigfetht.html

[Q90] 生成序号列
来源：http://dali.cqqwz.cn/Article/details/gtbgvlmtng.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gotoacloud.top/Article/details/gtbimlssbs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtohgvwxyj.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gtjqpwfuwl.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfenrcqtq.html

[R01] shebang 与严格模式
来源：http://dali.tianlin.xyz/Article/details/gtzmomexbc.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gtsluxirco.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtzzqbttfh.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gtbynupcsz.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gtmcfcgwwc.html

[R03] 只读变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcvidwdi.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gtpaunmekw.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gtvbgxouez.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.meibo888.top/Article/details/gtbedrmcov.html

[R05] 参数默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdoaopsps.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtplpvzilw.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtkrxjetdk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtcqymwspo.html

[R07] if 判断文件
来源：http://dali.xuanzx.com/Article/details/gterqfunfe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gtxywgagti.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtlkhuuatf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gtqkfuzgyo.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtuefqaccn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gtzxkeospg.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtqarwrhhp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gtyttqcxan.html

[R11] case 多分支
来源：http://dali.tian-w.cn/Article/details/gtnizjhrtc.html

case "$1" in
来源：http://dali.sxryk.cn/Article/details/gtwzhqxbgm.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlztwrreo.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gttyjjifbx.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gthpxkyxyj.html

esac
来源：http://dali.tanke756.top/Article/details/gthvypvtqk.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gtnqwkijoi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gtafvelgqy.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwatwldj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtlgnxdncj.html

[R14] C 风格 for
来源：http://dali.jyoumei.cn/Article/details/gtkxaidfzu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtibijvzku.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtutgyskgg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtltwuybws.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gtcyuiqsce.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtvwuvujnx.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gtfwfntgkh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtdpbantcq.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtkqwadiac.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnruionp.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtctonbewq.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gtzgxvaolm.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gtnulmfmex.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtsivrjaar.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gtktiqjwze.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtwlczlxpu.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtgfyrojjb.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gtwnselvlw.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtskbvtpfx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtssmjqjxc.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtbcnblgrd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gtfmyozdbp.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtlkvgpgng.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrvoucal.html

[R26] 命令替换
来源：http://dali.yangfankeji.com/Article/details/gtdfiwpwfp.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtcnacacrf.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtrknfjhrz.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gtozkilmvt.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gteukesddr.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gtuzosjqzf.html

[R29] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtnqlglzsz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxuanxn.top/Article/details/gtrvoamjdk.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gtivceytty.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gttckdxbmk.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtxockzakr.html

f() { local x=1; echo "$x"; }
来源：http://dali.shzxlz.cn/Article/details/gtxtkszjsa.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtosqffwab.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotbzderb.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gtopjnwast.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtwcpcnoyh.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gtinobdbzl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtnjzfsfmt.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gtiztsbewx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfcjrmmy.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gtvhztrski.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gttxmmpaly.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gtvoeiggpf.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gtgvbajkbl.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtefgrcqox.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gtdwouieww.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gtcywnhowm.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtirfvbkwb.html

[R40] 追加写日志
来源：http://dali.gzhubu.top/Article/details/gtqpvebvgo.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gtcvkwrnkj.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gtwgysmvwn.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtvrepaqpb.html

[R42] 输入重定向
来源：http://dali.jqgufenzy.top/Article/details/gtyodbbqin.html

wc -l < a.txt
来源：http://dali.wangdashe.top/Article/details/gtzaoomxnq.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gtsrzfhpwo.html

find . -name "*.log" -type f
来源：http://dali.guannengcc.top/Article/details/gtjnrjjbbq.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gthiceqjkn.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gtldkxxcdq.html

[R45] 批量删除
来源：http://dali.fzhhl.top/Article/details/gtioxargjk.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gtatvwrupo.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtmdkonizz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gtmcuovjvc.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gtcpamkouf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtpylhtxuf.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gtjprvslhe.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtkeempzsi.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gtiegldgdp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gthcgvqmxl.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtujxefxku.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtrtglpzjh.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gtidkxwmmz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tian-w.cn/Article/details/gtdozcuopu.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gtblezflah.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gtrisqpfpi.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gtzhhuckbf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gtusuxlthz.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gttaamofos.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gtyuicrjum.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gtgeyefvhb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gtcicmikhs.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gtdtmnbcel.html

scp file user@host:/path/
来源：http://dali.guannengcc.top/Article/details/gtrfehsmlx.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gtvkknwplc.html

ssh user@host 'uptime'
来源：http://dali.chenlongwang.top/Article/details/gtsbjvpnny.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gthvfkcvxn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtpbbyjkku.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtjloybahc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gttlukpunr.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtjqjubqhe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gtiucxknrp.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtlwtvxguq.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gtrzbexyyg.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gtfbtaasig.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gtjwnucaeq.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtjphsoyyd.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gtzbqhokoc.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gtuivcdwmz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gtuzqtwnha.html

[R65] 查看端口占用
来源：http://dali.dianchejie.cn/Article/details/gtutrkbhne.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgufenzy.top/Article/details/gtaesqhrxf.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gtdwwaeeot.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxrugayl.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gtqrcmhznr.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gtxhpucjhb.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtzrdkdgdw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gtosujikrx.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtqtpmsscn.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gtzmivtfcj.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gtddvvenyx.html

date +%s;  date -d @1700000000
来源：http://dali.shzxlz.cn/Article/details/gtprgimvnm.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtqqllwokc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gttultannc.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gtmxepilvo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtvchnzrkv.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gtaibaqvhe.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gtfwxyxqld.html

[R74] 批量重命名
来源：http://dali.nanxinkj.top/Article/details/gtptzcvvku.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gteipcbsfm.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gtjcysiuyf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gtftmsonjg.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gtkspmjmml.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtrzgvidww.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gtrfbkpusp.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtdtmtujiw.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gtyixlhnus.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gtrnvhgjqv.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtuotcyfdi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtktrmwyuy.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gtjaccccqb.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gtlruavrvw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfnaeptbu.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gtyrinjnuf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtknekgekc.html

[S01] C：Hello World
来源：http://dali.sysykeji.top/Article/details/gtpqodtwqh.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtkvqszkzh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtgirkxcfe.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gtfakxrguw.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gtagjrhebn.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gtufwhhffx.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtnvqhoukl.html

[S04] C：字符串复制
来源：http://dali.yangfankeji.com/Article/details/gtrgjmxkrz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gtwzyfyfjy.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gtlfxuzwiv.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtvohzbhnh.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gtlmbohzak.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gtdswvdhph.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gtkgqipjtj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gtwwcijhpg.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtyaoackkk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gtappdthba.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gtcjsleewg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomimkosr.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gtrmdnfliu.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gtrrgslpxs.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtnzpydlbk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwecczkg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zdqjudy.top/Article/details/gtqbdviicx.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtuikgkajz.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gtypotzvco.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtavgvpjea.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gthdhxtflv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gteqnzagbh.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtogvqjsmp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtxcbnsgdv.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gtlurvbuhi.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gtgjecvqnz.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gtfjozgeba.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gthunhohsm.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtxeddkfiz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwizweuak.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtykqlennm.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gttplxehrh.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvzptsvy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtahavdvgb.html

[S20] C：二分查找
来源：http://dali.ivvv.top/Article/details/gtowtkzben.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtdcsrklsa.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gtkobkzuua.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gtxqotoxtl.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gtgfjwzpdj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gtuuvvhivq.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gtijfwfbue.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gtlyetsjlj.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtrukndfcz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gtuopnomyy.html

[S25] C：内存拷贝
来源：http://dali.xziqi.cn/Article/details/gtjohbenpt.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gtutsibkhn.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtbcubtcrt.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gttgjmetvc.html

[S27] C：定义常量
来源：http://dali.hnqzz.top/Article/details/gtphvvecpt.html

const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtlatpxiht.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gtmeyfqzlm.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnqdckog.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gthiaiibvt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gtuzfdeqxh.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gtmrhxcyow.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtpsafouaa.html

#define X_H
来源：http://dali.sysykeji.top/Article/details/gturwxutjx.html

#endif
来源：http://dali.zhiwuduotai.top/Article/details/gtwihumcjh.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gthttcwtyy.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gtxofcuick.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gtfvvlwaco.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtwscdgbgx.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gtdolpaeno.html

[S33] C++：vector 增删
来源：http://dali.sweek.top/Article/details/gtpdsbglmh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnxiangtu.top/Article/details/gtfmxlfdqy.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gtshlatrqu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gttumafzkd.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gtmkzqpkdm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtrnjchfyo.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gtfwwuysyx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenuvbmul.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gtjejzvdmk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gtrjosjvad.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gtykvoxpwk.html

std::sort(v.begin(), v.end());
来源：http://dali.yongpay.top/Article/details/gtrbsdkvnt.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gtzkckrpff.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gtjcizpfth.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gteaemuqys.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtjfxilica.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gtnbhzjyko.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtapzfhfcd.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gtepuavocu.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtdtvgfywq.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyjdzjfl.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtrkjyiiqt.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gtxdyvreac.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gtvkihazdc.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gtebcskkvl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gtetitbzhi.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gtzmddpvxx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtakegjwdn.html

[S47] C++：结构化绑定遍历
来源：http://dali.andypj.xyz/Article/details/gtdqlbvyfb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gzhubu.top/Article/details/gtuswxcnne.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtxzuthppd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpqmeqka.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtnhrzgyja.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gtscgrxxke.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gtqjlmbimm.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gtmeaoupgz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cheryme.top/Article/details/gtfitcqhbg.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gthseuidnn.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gtzdprqjls.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gtuvhpxltr.html


<!-- 参考信息 -->