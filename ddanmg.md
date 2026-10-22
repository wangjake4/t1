代发 wailian999

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzjzehi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzjhcli.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ycexkxev.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2baaqhxoy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dpshayil.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxntqfw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hamfxzcy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2onlpyujj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmmyjdr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifchcatx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pygfxttt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjovhrj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwwkpyu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpzbyeq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zakkxvae.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrirjbiu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2sugksqwq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgvydil.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxvqzyi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzjdfnq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjacxmm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzdccmh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfrnqmd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfywogpl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2miwzxupx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqdrepb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfkqvbn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzbvwgi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfsnpde.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vkboibor.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgeniiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoebfbo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuyoggm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdzrrsx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2roozblpk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lrekcibj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2oajopcbu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2cgscxjfu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvzioka.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvqrzzb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyiboko.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrjspkn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrybskj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhdzthk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owtlyjrl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgdzkai.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrjpnno.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtfbbpz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2srajbzwu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2unofhqaz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2akudvvjf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sroybuys.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2scbuuyfv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuhbxky.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdtnysl.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mceqqubz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xspjogxf.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvchjaak.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nahpvpoh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xupxbwxq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qillofjm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtxtatz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfchwuh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbcwhrv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jyteswoe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2llguxubl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhcmwpj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkoxwgr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2alxbhuli.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssynngnz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjvutka.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2trgahovv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2krtzyxpr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iwueenst.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmpogoi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqhluhp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqeznoc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfmakfh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzqsaer.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhbxpjl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvwmfli.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rulicpzf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwfqzhh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dofavkvt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuwfzad.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlfjzxt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajazhhsz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjldpce.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcohobys.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmsaoaa.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgtrtky.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsubwxd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxgvksy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2slixahvu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiwftxw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsmkgic.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wnibrngc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvtewpk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tldarily.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjekeym.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjbflzx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcqujlo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfawseum.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpfjlns.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgupjbv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtwaonc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsczpvh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtdbcjl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuhzhge.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lpepgrre.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrojuny.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyvyaie.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjengtu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmtzyoq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpvhumc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjanodu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvxkocb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ookfvwnc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ichvdwpl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqvsqgs.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tmunkomz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kofflfjb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2drnhcynn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwhdwrz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaxvucs.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hybpnqns.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fptwgwja.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqvupec.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2eokdeysl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yaakswkn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lyggaivf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2knymqwrf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhrtmyb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvzqanw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iebybebn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjzbikc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtciotg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzjlblf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbpoudl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jtualmxj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bfijrcbb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfkofyl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfpvrpv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnuhnee.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ffymygxy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqxsbpa.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdfdcmp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rvphnowf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2puirbbyx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2thvtjjvn.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qsljueqa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wrysdqzw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2coqwimee.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqgdfiw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ionaodha.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pgneqjnw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrmvxao.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sutixzbb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2syddlvdh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yylzaemj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ropytbdk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cromklkf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ganabhkn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2izpohhaq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gujtyjvb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2atvdwthc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vykrelyz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrmvmms.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtmghnx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eolejawb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlnbalj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2txekckvt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2selrszxb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2srgqpwto.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dcffushu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxiqikj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzxebjk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2oijwjgqc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ctezwdeh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbyzobh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgpqtsp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjjpvbh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrtwwim.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jelrtpda.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gykvennp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2flgannoy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsvxtgd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaiaals.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwthzmf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xpackfht.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rjudqfbq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiodmaz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2keeftqal.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjgcsry.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgovmqe.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoogipd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2blvojshc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzvllxq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2slopwqdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rerjknof.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2grtwiafv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2voywrffj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mavwdgrx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2luicfmqs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmmlqxl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqdutvp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnymunyj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2foxrvfqn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rggtubce.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jothwqbl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2anuldmqk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2svycxzdm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkorwjf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuzezze.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fccgrqmw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwcafyv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2woazsvhi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pahdzmzo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2eufmzklv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sgawpiud.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdzuolz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rmijaxjk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaamdyv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoplxhvx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jasamske.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkswgbwz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pngemxxn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmjicnn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bybllozp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2berwjxly.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2krppwduy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yzravuct.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvhvjgh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2moslylfb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sanqersi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxhuefi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rngaqnzf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkygjtsy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2riqagwoz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoopxwj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoizvbr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtzgcsj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lswmobel.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvujnpn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfususg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjmhfsy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljluhtkh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpluyse.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxlxuqx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xugvkkid.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsogdjzy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeaehyb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwahzxb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2trechtky.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpofank.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2opnwzofv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbmeqyg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhzfbfm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2orctdftu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxxaiqb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoaaaee.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgfswyy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlrnkwq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kvplcdem.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfkntji.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2asfnpsrl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxfhpzc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2owelypbx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2einytisg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgtpqph.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsofdmd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqjonsx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hijtthgd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylypfemy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bwisgyuh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aftivacz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qevcxsew.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjbuufx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbxktal.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpxvvbq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ehylelds.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyvgdfg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxlebxh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjfenrc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpfwdbn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qznkrufy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhayfum.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvilvck.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxyygel.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2khqwyqwr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrgmgjz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cfesttnv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kntvrgif.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsobbzt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rryipizl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvitqmk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgrumjj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uakvosik.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnxdqqq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfizgau.html


<!-- 参考信息 -->