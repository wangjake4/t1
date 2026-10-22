代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmqvkxi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqsllim.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvzsmlt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hufcbtpq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyxkdfx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhexfvdp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxnebpu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcmhbsl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdlblab.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbvgwjr.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cfacgfwa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2syivmubq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdxszce.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyqeszw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmiwwti.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mumninvq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzusvtu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtpdnzx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrfohyk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bagpalgi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsgbavk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaczqeg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sckqdqmo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfwthyg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmnfzip.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdeelmw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzmxfqa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaziihsn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlnfiyt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2troqjyjy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovntinyz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgzmmeo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yozwysnp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsfatqp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qugfslri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uungraol.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxfqnxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvucydt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fndvpalh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kayyqdls.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfiyqrf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2spasogde.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpycmaxw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmmwoko.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2brnvwela.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlslokcy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvagphju.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkgswyq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzowghkd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjejnnx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sappvomg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfgmyfc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjsfakj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2icsvdvic.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbqgcnu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjerken.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpcjetr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwmpkup.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zigepstm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2urungxtm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mspaiiwn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhszkfp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdeexvy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgfusua.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2flxozhwg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfstaitj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhxqiaw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmgjlto.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlfeqhw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ooksraoe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwaxicr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxqoczy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2czqxbvrl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiplftm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2adchmhnt.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxfuvlv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2icgbnbpi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kebuxbph.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjggrsy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jhutdzfk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nirdfhqg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nluskbjn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzjxclr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsafgpx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtdqlzw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdeasbj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhdxsug.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwlpotn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cfupdsrc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzzfjec.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzimlcum.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdhmilk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmztiol.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhlkomf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2endtasoj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ptehpvxl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdstxmoq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqkzfzp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2boiumizw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgglotgi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtnqceb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifarglpj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsyojvu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfqxhlw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvhovhz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxkwgxf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sexflgvj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2frjcsxok.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qvypfhxb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2frekhnth.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2epjrbjuh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2refmxrow.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyrxgfn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmyrjkf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbsfgoo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znpibmqh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2awocawie.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdkoezn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpfonwp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyaobtk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjymiow.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lrosdncr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2liukpnmp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kifytclv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpcgtwc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vywczwdj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbxnraz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2osffjmbf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uyliucph.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgoqgzb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rthboeem.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2crkekevk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgnsntt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrklqwn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mflkbhoc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pseigzoj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcgqksz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rycloxvr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2smhjgsxg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmkqdbj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfgbflj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tybkpvua.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ggldgsia.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ukczkrts.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fajnvwjn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehomegbx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfnwkol.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnybwbo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjhjqni.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuvgyuy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xahzsyol.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyexvmk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2shhgpfvd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mohrydjr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlzqtao.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2grmpdmma.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pkylgywt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2foaiucow.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fszfqwxt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxtvbic.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkwmjgv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2keohuqwv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjrufut.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dulvxdbc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cxizcqiu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjvzhta.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ocngoxwd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmlfvnb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iufjgfqz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wpieifya.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoocoxbf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bawrxbpx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxbbkcl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rdosdttl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeiamse.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2iiftcovk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvwrjso.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbtdidc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvdxesm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cczqkilc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhprhgj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ysytghgu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjrbmtu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mapmfpxb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbzmhph.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdapqgz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xcowbiyy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnxnrol.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xwduaeeh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2inywlinu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wottisew.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfatfis.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxmpbhw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpbdadm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpmsnwz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdqzztk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2royxudlr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqkmllj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrxeaia.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dflxpluz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgdlhek.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbdtipr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hryoralc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvuoixl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gzafpxwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwitramc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axrpwfeh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxehjul.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvabxxo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gseckqmd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbwzpdj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwfkqup.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqhabkz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjbhilh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eysmgaog.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wefyeacr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxndmuxo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2msnaocxz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyokxfb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kghasfml.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhudrkt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ohomwsbu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjkirsg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnxfuzt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtzuzce.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zulpaads.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvkerbf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtoxwgi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvcsjeq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnxieli.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjklnmg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhtpeal.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwjfkan.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiygxyf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkqydej.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fvelcefw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqmvvnq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkijjwk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcxbkdg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iponrcmw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnakuqs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zipaycjm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhtgcmw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpjyfjc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vidulcxb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyhhynt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvlqvwq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rwntieuf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmntipve.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2itjevcdx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvscowmu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxztpdz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqddhag.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqghjkrl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2joxzazze.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpjdgjr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgajemw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2njmfstxi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcozcwut.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xokszmjg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iibaarac.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2blvowspk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcvzmvv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcboyrip.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbckqzj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xyherjba.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnwlyur.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2flzyedja.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2notghjje.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqttnax.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhenpax.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zelygsvp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2adpafvrb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxauzyu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqbzwgg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxrdzcn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2iztfgnsc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkrtsyf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cyambusr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkcsjbx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyogpys.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2krxtglje.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpasmly.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nglcxmsk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2afhufqhu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqmjegb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2julhbczv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaqcsyx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2twjwcull.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2diytfqvl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bipfmuir.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvbwgxd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2alltxxbm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyvbvpa.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuevyvg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmnqfbm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xlibluuw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpansri.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rludxjjd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eydrhxbt.html


<!-- 参考信息 -->