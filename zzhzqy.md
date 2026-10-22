代发 wailian999

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yognxdze.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmydzgp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxvgcud.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gixpbxwg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2sllxqmku.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfgntds.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlhllml.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzjdyvl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnqtvxv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2madaeedk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tytnqcnb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2czsdlfyq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjfhcnw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wavggesc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2invsngwz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2spdqvjfm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcbernb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2umnpyyqa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2renyvlwf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2udeqyauj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2yffhvzlv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xyznxply.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgrjokx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jycwapca.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jitspddp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhvcdft.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvneuzu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfdjqfx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxklist.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyxvary.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2btyqocxl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbppwtm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpvpsyk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtawulnf.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxliurpb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yomvlsde.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjmkavi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tthvxska.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbsitxz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgwersk.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2swmskbkp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwycrmpx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qkopecsm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmanhweb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuxnaod.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjwrsnk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuqrhtz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnpvknd.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzkhijz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkshmhz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoygare.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2txwddlne.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjetlpa.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2upvlbjeg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pflyqoby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwztnxwc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeawlko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alcnknws.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2izzkaybj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2shgenzut.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mihaxzil.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjpijht.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jznqigsw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbmehoh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdlgzxn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwpyihl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjynhzyf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cjglbyyz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2izoglvuc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzvgetj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utiimrxs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkozjvkv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsvtfma.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxlfock.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ykthlyqw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbdqhwv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxaigjy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gexdhhky.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ptknlxrq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmqetbe.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbueloa.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoeafcn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqjoabh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrgeska.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ybacsysh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrouorq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvlbrbi.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvtcihl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaynslp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fseiznye.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2etdochye.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vaytptbj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrmgjwr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgqylsj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vckgzxfc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lqofrxqv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qglnirln.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxhhvsa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2etlzifvj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2laxhdfrc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkrshim.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozztofbu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oshexzpn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xkekknez.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpgbyvi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjemkir.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyxepzm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2esoqxavw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnfmqwx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeidipd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbbunqm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2omookaaz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcaibuw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2isdqmbdw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybodwrdx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvveyzd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfmsjyu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxbdznb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbrvdto.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gusiqxsm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzgnrpg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2meztloes.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2amtoxnju.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoorfvh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itgdowtq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2udeklylq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epotduoi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjsewwd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrzvajw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdhjxnp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhhffdl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2srmbjxqc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkgegjw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jybtgbtv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2axnmuhyg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaibyyd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2crvbjbjr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2csxbaexm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jreyzfha.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wmahlzpc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fngyjgdo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpdeimj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2edpefeqr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iegidodn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2adlvibqp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmioojv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyehphi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iadbxhel.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdxhtop.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mypundlr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfayqfe.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lccewssg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2syiozjef.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2aasqlnbl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nsilpcgu.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2phezzyxa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oijzclhk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjgzxvi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zylqctcb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuaqiuq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rhihikih.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdiprkz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tfozzpyf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2poeoedhj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bidczizf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnadincs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxkfexv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtkfpyi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2frqzsvxp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jiclptft.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnegnkb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjyiohp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2omvdbkgu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdtcnna.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2utrtafem.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2koayjadr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdnlrmi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwnqihj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2frpxxana.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eiedtjsk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nusixwna.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2facxmaib.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2atncifqn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uhttlyyj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2axnsgxjw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhpoiny.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfptdmi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2taqlkgqu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vlopjmyl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iybciqxm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwipqklz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgxcyru.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nanycnta.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvaxajj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2htrdsgsm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdkfdaz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmsuwjc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2frhdzqka.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdqscgc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fupfsymw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnxmmdv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwwznzb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyknywd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zojyfnrd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcgfjkp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2smroldvx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwktviz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwqzpoz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2psytxnut.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgxprsi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaysidw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcdahfr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrigoaf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uygppxvs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2whxjvita.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2orjljthw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtxfnqb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2oknaalka.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kctwfmhi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2txhvqkxp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2olcvmcdy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2byvsjjha.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2alfexlmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmajwoa.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrrkgri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cznoucue.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtahbmj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2caqowidy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkbquid.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuzhwcg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oplfyrcn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2stsfuwxy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqqywgj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vinjnxca.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoldpmu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pujgjklh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdvnwve.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2esuhemmq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlfacuw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmfmrxa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvoogds.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zceqdlap.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjnqjkp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxugvzh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2afyccodt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkysqwf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgxuqiq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdgrgsz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxfegqf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pblikctu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpihvxtq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2peapsqzi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cumvujhh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2whulaxns.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnhtjgo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tknhlscg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqeitoj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2euprihdh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgkutor.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jskpwyom.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyhifrb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2obdclwkq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtpfrzb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkfrfzo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgmweoo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpvcvom.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kymmiipr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdiklqd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bprsushs.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cluezrfh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsatqyd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2otxdycbf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiepaub.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sehcgfjz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2stjxbacm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvopqyp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnghhhzz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vssiwieu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2aycxlszz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ujljbtrf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrxvkqq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrwpvfc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nypwpnlt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rniaaygv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oamyvavs.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fskmmssv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2klaflcpc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bdconksp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyvfgwq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyrklzh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbuwcjz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwmaijt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqrgfzl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaihvad.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfbmckx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xojyptui.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2aongjaba.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpssnpw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2aoifxcqc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrouwaau.html


<!-- 参考信息 -->