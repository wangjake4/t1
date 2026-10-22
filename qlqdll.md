代发 wailian999

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeawrtb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2teyczbqw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tucqhtjj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2csxvqvag.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtopgix.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkjfvoi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2stcypvtz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqucswzf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcugilwv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2imyhcguc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2suawutun.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2veohdnto.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ernpkrvg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdmotsa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuvvual.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sziybblp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnidzkpl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2siakmzbx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rchcasei.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrgcaap.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gsphtalh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iywutjja.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2djzsifnr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2feypohsw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2esuvjalq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcbtpdy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyzxgor.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2laqtjjgo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jwibrzby.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2trnrbpki.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sbthvhec.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtfqeuo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqchaef.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgygsbdg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfjdtgl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdckycka.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhgxidz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdtgjyk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxnpqha.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwzgxfx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2oncuqhvy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hheocons.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzjtbkj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2imuxhluh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bqffhuwj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpiuhvz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kijwpjsu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxroetrj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmofifhd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lcprwrvt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2guezzqqo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pudeqpeu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjxhyxp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcerfsf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbeohkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzcylke.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqdqopj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gttofmaz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvxmprs.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zblmhaue.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2prqlsayz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tliymavb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrmmmay.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bthokpnk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lezbasfp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2skudzhcj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhqucpg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrywdpf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmasdlv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aupqhadh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfckuakm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szscuwjb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nhueynhd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyporhw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wegtkvbl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnedxfw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2awpudzcz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vtibfkpc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eumpokpx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwqamsh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhtqiiq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uffeqiwp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xchlsnss.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuhzqyt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2iuozpfau.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2plugvgwl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdqgpvu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2czrtqhea.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2klrjasci.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rstlrbyr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzarlvu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brvotyri.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwaxjqv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2efafsttc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2utjubodq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2egxpuzas.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2osvkoilu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmhodwt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyhfryn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqneqlu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jasyamny.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2aytuvnid.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2liiajloz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpxawtv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgvpuzl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rryathzl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uferxxem.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvmspnz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eulodupu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnzftsl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eeamxgeq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlttjii.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbkmzge.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdbqaev.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpaaqhx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2iirmteoi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwftcct.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhujuyb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaxnrkt.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iibvbeld.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dwphjjlr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuhvfut.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcbvyrb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvwkkfx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyenznua.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lojmekdp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhtewhg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ifacnujp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbwiget.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkzinoh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoxrzbu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzhbhbd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxgfpqq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuyunpb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtnyoxj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axkwvbkd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbunbzts.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxpbeqm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mkontvrp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hejhotwo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkpsbgm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jaguzhab.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2czxmjejr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrnnfrc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2flesafnj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2moldxfof.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnhvnad.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnhwinm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjhltly.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2limmhcfh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oxerhmzp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgqmxbb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcavhug.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kyepqtma.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2iqengcok.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpojcpg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2munuqtob.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2implsxhh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kormucsr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxvgzsa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbvxmkx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bruckcgy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fdruqpgl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sopbyuip.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cujjoinp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpzezsz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlzpozf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2crihugjx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qglanyua.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtrfrbk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2elllgzvl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwrrnux.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2biukhjoq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eawgeidv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2alrmrtja.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbiobrt.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gaywatas.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyocmxrp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2twxnuvqa.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cylpdyju.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqcjmfm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrenorp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlpgdix.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qbydtlxq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvcwnve.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yizlispt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsxmmpn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2itoihble.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ziivrwjv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2awilzspp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2njzwwwlu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtuttkh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuqfmto.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiqdbuj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdpiaqt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmmqrkv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xgixjdxu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2iuetgbps.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uuczxyts.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2safkueta.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqysabi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2iihezsnn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2quabslwc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkrwpws.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2iooccqcr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bufveqpz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nduqnhxb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nczkmgnu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgftpcz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2loyrkwny.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iyioewmr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoagtvm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nteyzlye.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idngyjqg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdvzopc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mltwokcf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfsqmll.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrowjsi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2srjurqqq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2thweoboj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qrofexut.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jfntione.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2oavyuzzt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alfmjjhg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzbpahe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjyvjpg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzdfhbj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2swwxbnnu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkrcsma.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbzwrrg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaaougs.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2weeejdee.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuszxftv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwzvhbq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmbcooy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyfswda.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkocwpjr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tphrwdpi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhzafrb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcrozkl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxlagde.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqzazwd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mapdckis.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2shygbcbc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtfxmbr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lluevgkl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfvdmre.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fixzbquv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvbynal.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2thmhnshf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeomndd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdcjkfh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkmekjs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2paiqxuoq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2obaqcayn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmbcbuq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fwymdhmk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpafkgn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yifpuecx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgwonaa.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eleonnrc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2naphwyqy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvrrbgf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdavevoo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdjlvxi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2okmgomrl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ketenmgg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsamfmn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoccfrt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pxneljmb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jobidecd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aumxvlsg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeekskk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hflsidtm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdxfnwz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2elgjbcet.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wstokvvu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmddgrw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykijjmgi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2texnjcqb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rplbvlmp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcbqouh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2orlegdob.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzgkzpg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfgyszg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aljjecaj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzpkgmp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxijram.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqcopwa.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2imvkyuye.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxwivaq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xphcacom.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bficywoz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsbvala.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpdlhqc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsxnjez.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxcwrtn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhunndh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbhhchy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqbsbzr.html


<!-- 参考信息 -->