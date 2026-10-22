代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqopbxl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrhrfhg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2luvdfwnl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gexzabog.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jogunlwy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nslgbusc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjcftls.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdphktlu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2alotnnqs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbhmmre.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2koiqjzba.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvuierb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2klplxlhj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zauoophw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwapamg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnlstzm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkqtwdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztodioht.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqjxabm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbjgcob.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgilhyh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rfapotge.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxozdqzz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoajilh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbmixme.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxmxtxs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyjfuvt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnbvulp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2graydoio.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gonvjcyy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfjofgj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnagnys.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvdjfnh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhlgoic.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnmcbql.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwjqnzq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aurduluz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2khybuukc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhzaina.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qpanlvaa.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtygiof.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjhaouz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzsscgo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gayaewxp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmcptuy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwqrmnf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhvskqn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oclhxcol.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dowubobq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dbquqeyi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aumvudrk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2inaerjhu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zakvhxbh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxandqy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oyukrmxa.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtnpssn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkmbexf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbourld.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxfxmsj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2blqffhdo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmphdds.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ornybbrn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvgqdvu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2grsxlber.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2slmmegfi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2imrgsfuc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2htozgwqk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2whufrzjw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tazyjovr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgiupib.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnznixa.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfmgrrp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vecdsdog.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wpinnten.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ushxrbes.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbkpfmf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bngrcldd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwicjtb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrpgeja.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olzqqtxq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyovryy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rninujmn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufanxrxr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqfmtza.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbydvyt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2akznokhw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkquhnw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsdqspf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmfxwtb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrzljnw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaonafq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pjophlkn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkkrnwk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmghimi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcjbzvi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fitlovzo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkawyjef.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2litgoeji.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxqqpde.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbxxfqm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcjceiu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkwiqay.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjrqico.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hexnwpze.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtibodh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgqnwyz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dehnhkmm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igvqyryo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bjavmvhz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vvughdux.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiceohs.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bzadfrsu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfwdbvy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pketekcn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjzpuyq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezszgwvg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tjisifqu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pinitazl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xlybkcqj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qfilokuz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwntufa.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yzroygiw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbrhuni.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbfoamx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fhndchun.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjfiuco.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdzlrus.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2diolzlbs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyqqoem.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsguomiw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tsozsird.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwxvwti.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2elscphgz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2modqrcwv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsrvlaf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkatdrx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2djosjjqs.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxdilph.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2anlkioxi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eiamnhde.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2linbxgfb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvelawf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gunucpmy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbywmlp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdkhcxm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgewuuy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsidqsh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdvwxra.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnrqudl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzzlhlg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxavora.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgbrifh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfsfeju.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxbhbly.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2iemkfovn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2glcwlioj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zameydsl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvqhnmn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuureha.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwpvndc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xmflvucr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfymqyw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrborwf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jscaycpc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtjobox.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xoafwkvn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfxyaqp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsfrmcs.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbjfsxd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvcyzof.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qqceajnd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2alntfseb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzicfarb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmuqqwh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2opgxkfhk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nheqbzqn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kaokgafv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yjktscgc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvxoksz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbnsznv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcguxyd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2roomhrhl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zukrmasq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smogayfm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hauqjfpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrogckf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmxuxnc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaczkzq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wszyieuz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2occjpcdb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fywbdwfm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjapbkp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fijcomiy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhecuov.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iiljitsc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ginubqtu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2youdlzoe.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzelwxr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gomvgeml.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxalwwo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2duybxdmw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpujauk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnicdmm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwzfuxq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2oncrgzke.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hudvzmjn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzguvxkc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldabiykp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lngdlbub.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jugznosi.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2chwpudey.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsgrjpv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rouugnwk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkpzugc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsnxrkn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dywugefz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqbzmyl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmrbzuc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tryviwms.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzbcfns.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vivoqugm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2omggbslg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwpdwsv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2blufntxz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuwwcug.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2knavncuf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yasdwdbx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvsvvav.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxspatab.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bdejunnc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtwfgnn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qadcbklb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsatrfu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdicsmj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pydblvae.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdffnqy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxtbndo.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qofqiesr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqwyaoo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiyfktg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aowvorna.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyrnvjy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zesfrzxg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uppeoihm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkohatw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oytwlrqw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2elpkesrw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2abscmoig.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkszssf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiovyib.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cixeyrzw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrckwsy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqjmkxz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpjwxda.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrdpyed.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bsatiknn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2oogsfgdy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2amxcausw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmmhhsv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaxsfjk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lzphlnyk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvkputp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qymbfvai.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kanqkjoi.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jeconzep.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzlcume.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfthglv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uamhvmkg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2onnajcbp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzdzasx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2feqrxlus.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwlcgvn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mishzund.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2usfwunzd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfcvide.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2deocpjnj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2olduakes.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtveceeh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2taqfjfzs.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrcngve.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pibqotkq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nkocwvlc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmgknll.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upjatfcq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ttejgslv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hktsfgbs.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxqkrkk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gozsqmlb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtegzzm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xttakpfz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpwlhqo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fzogychb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxcujlo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eueanald.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ucopnqmw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhtpujh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdsxyrt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbgfnpu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2afcekhza.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzpreff.html


<!-- 参考信息 -->