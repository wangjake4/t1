代发 wailian999

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2krtblzgr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmruagl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ervhkace.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2aiximmph.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeremgl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyhomsx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qcouljio.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdnqzwl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyjtldp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfqjpgg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbhcsve.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvzumur.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2beocbrsu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvfibha.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnhvflv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tprjwvev.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvlkqke.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqqjpvd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgprhzm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zecvjjoz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hskumwcc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmlvowc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2suuvqeuq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvdjzsq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouadwuhd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2oayiswwz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2icsihqcf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rumtxhla.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrpokdi.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qspjyomp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dekiajjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2byocznzi.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtwvgjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cofrvobb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2syaboxec.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgphudj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2juiphsgw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2yaelzufn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2molexusw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2akvpcmxz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrazmew.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtpqzcu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvqloyx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oispfnod.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhhjgzd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrlvkwa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwdvwgk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcyqdsj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pznoriex.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmooxoi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlzlmhr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtnmjsi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbjlxam.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsffbts.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlkzvhf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2psmugoyz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2acihbuuu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnrdhqw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mufvasmb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uczgjldd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrylirn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uicdhghh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqhgeqf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvydayz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxsbfwi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2djzmyivd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsmooeo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkmtzfo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlzsyeq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmyfgre.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmaabra.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2azugxnai.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhqaipe.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwtmkoe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2flimnvqp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xplvkadq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcaecxe.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjawxim.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owarebic.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fecyoycw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyetqyn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlhloop.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmqjgcj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvbgord.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkicvga.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gnadskof.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2onmkhdtu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bifakjxg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqyiefa.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmtwiht.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmpmzrq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xxauyyss.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fabgynoo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wvopjmqo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhofsnf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sobfgwxo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzozpyy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsbvcgs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnrxvqz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmporpir.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shuwuzlp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2prrbvmkf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrylctj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nofuvzwi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwnqkeo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fokceuou.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tacbujqy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuicmpm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwekuvh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ndafqjbu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbxphuk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfswopgo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2skxsemwd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdyfbsx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2opyqrvlz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2geuonzvt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhvuayg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjgatjq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvmpkbj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbiiesp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqvmzme.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfguhhq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qwivnrlz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqomdbko.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yukvqfmw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbctcrw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqxbuvd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ippkybtq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcshszw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2quvudqqt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2miktvxzg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgtqdat.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkxcejz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eojeitul.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jciqqebl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmgazxu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2obzwcnbc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvgtuno.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdgbwyp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ydarnvdx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2stlekvuj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpqjkvy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uiivjvlz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcditre.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjjhxov.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwumhwnw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ospwipae.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ozshzifa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wpppuhjb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhgohyw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhrkjys.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxcsctx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmbbfum.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cejwqtva.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrzanyv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yoifbxlz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2umapgkvw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvkffbr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2febvqpkk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nuihktvr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyrifbu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyskxev.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uovjkecn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qijokalz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xqekwhzb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlhriuw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2srcjlzje.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfcccqz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxzqicr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rlauwxzs.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xruzysfz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lidbfact.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdkwqat.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhbabaj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2frlvieby.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaoione.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrlipob.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqqzzuv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2llbhvdfe.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoevero.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2aknomxzp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pamokurz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsbxjap.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qxurkmyk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2eerrttjj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2crnkxxey.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhgswrj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnmkafz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2thozkrbi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2toohorjm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2apjjsnlu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrbwiwz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2djqavbeb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2plucbvdv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2edyadfux.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgjctjr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jberxepd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gayitvgb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdqmfzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgmgegv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jgevrdgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkbortb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kngrvkic.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ajleqcsd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epympyub.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kripkrwo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeeefae.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhryeueb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmbqlvl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwhlekt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tggggytx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzwjkqe.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgumemg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2azyzrzfw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyjmiyh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oekjuylk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtrpcfp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2swxnlule.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cejlyvlj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2keqjnxhz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwhmaum.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yunxkyoo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxoxsdc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdntlhb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fthgsdgp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cseecjwd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2euwrxlpd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2koasvwxd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2elvtspgk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwmrmko.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnysyvvd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qktplyxc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2adwbpcxq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2unjajslb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvswcva.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xsevujtv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydglbkrf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaynvsg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rysktbqy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gplkrxcv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmkjuwz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqblagb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpmrjnh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkdkqsm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdeyyic.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2morzvren.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwlycje.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbyisxk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqyvxgx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2silsnvxq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdzjrjx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmkqguk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgwnoyv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoepznk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2smksytzl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrxsdwz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkflvuai.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2akkynpfx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcxrcnl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfutjxc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuiryys.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnmeftt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxhpazc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2osameoqg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rttzwwoy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdzvhuz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2unjaerjd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2icnfpoxg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsefnti.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcahrqsr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhujfpa.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uelhgtft.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2trzkqgug.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqscqua.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwojbxp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2marklpvz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdoinpg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqiihkt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuyyarp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxopojgw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeavval.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfvswck.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sihlayti.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfmjbew.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvlqkke.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2azoxardx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ktptbidf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpskyhdj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2plvbmzdd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tulpcvif.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjxxgea.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2axktaqoi.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2myvdxrmz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2prgnaarm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2oicpcnud.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvbtfgf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfgumrf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2akdsdljc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pwozoiip.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqhjkls.html


<!-- 参考信息 -->