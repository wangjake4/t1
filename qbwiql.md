代发 wailian999

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dcomdaea.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qoksldlm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdxrvlr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2crddtxvg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2msladntu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkxzpic.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dvavdhxc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2arfbvcqf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tlslahtz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kawpkyjw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2umyocspv.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdbfaph.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnwxabd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wzybbpvx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cbykoqnt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxmrczy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxkmdnq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwzzlxv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbvxtpu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zmanssus.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyqtfmh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wnumzjsc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iusmiefo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oocrgmds.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwkbpjo.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2azwqmfvg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbnwtnk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvxviig.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpvafbj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2inhytkpy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqgkmuj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpkuqjy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2szxcgcrk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcthtie.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2crfhdtvr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2eviqrxpl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2memsobyo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvbbxec.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uplilpnx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2duphfwua.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzkekea.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gekbjvsb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wewnrvwq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2llwjrzgr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwdrqxq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsjlltu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbdccgm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvshues.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wizczxft.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxyetss.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqhjkqp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhygtihs.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoagyiz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbtlrsd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kasxegbw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gccpxyze.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gisnutom.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2autasnkc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvmhuxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwtsbto.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiqulsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2revyoemm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xyivzwiw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2oqimougl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxnyxef.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2eatvdszu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwnaqwy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tevytbed.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeqzpmk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsgqdrb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xicitasg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrkohwk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vapgmckj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zpypkcxs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaauxkcx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hghoquit.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qendryab.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhpgyxx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvqpftc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgvkpor.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zvblopmq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcqbmzt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhsrasx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rslsylxd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfrkagq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxtvjww.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuwkhjk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2flrpiqcm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ynehwkxv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfjffjx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqouokjt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gtterxuk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcpfmig.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2okoiebwi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xahuawhp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igygbvit.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfzauak.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsdnngx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfqxhgi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jacnkbix.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnztgbo.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2slaqzfkg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcyqkou.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqdekts.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rouclljh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bibuqccx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvdjihb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2khwnyhni.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjfdzic.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbiwsfj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgbilpj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fmayhali.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccncjpvi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpiryrj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqfqumm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtsbqjl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiokujw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ournxcwt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrihfff.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrbkfwv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrifsrp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhibhwq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmgjbge.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgvkxtb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzenbzz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qpktgvfr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2txdohbbl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwyvbjm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlvqory.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xfothxmd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdflwlwa.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgczzkx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qykfmdiw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bmayzlip.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2csrrirzd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jffiynbh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2swgiviaf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dubkhnfy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ibshdtxk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgpcvvg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vngcedyw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wulabrau.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uygtratu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fewfldla.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kigalhwx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xrucomoi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iksqofzg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbpdkht.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwdfeng.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qduijcrx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gwexwaly.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nulolfij.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2shsxapqj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2szigknpy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnwclfo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwzswqh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ovupfaje.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rrprgqvd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlrymqe.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmmbrlq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbwjnny.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2akksglgs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgrbglm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yatnwuwn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nritqhow.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcztzer.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tafduddo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhfjkxk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqexwhq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvxvewt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nidhphht.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2baanhzmr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwberty.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iistejhy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2myloerlc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuhqhxm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zqppwpwa.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2otkxbbst.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdlgwia.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjjctmk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtatqox.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcvwtmj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2btyhnkkz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2moafojev.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrmpucl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2avhgqgkj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtonsgn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcdchfg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuvcuvb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpmbhtr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jxczhbgd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrbdjeq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2swvdbuxn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtymgva.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrzcend.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkzlxer.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jfljzahf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbxfgho.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2coshjqwi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvytlko.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sxncmnto.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gwylyswt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqmipms.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xidzxltx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sipgixbc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhtcsib.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gninfvme.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2forptxze.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qadmmzhi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zoedsxcg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2quokstji.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yyruoilv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsnhggg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtcingd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmbisxj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiodmkh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tigamnvb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqajaxxm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rijkpjvh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqkdtxo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeshtyy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlsfdws.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqlwoui.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2quzyjvzc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2utedbcpc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuknjhf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kglhwiat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcyvfrh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfsbtwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nujabtmm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xqraifyf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rzklsntd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykafrblq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2unvagigh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2brcvaqwh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqizvzh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhnpaav.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbnqitc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaaujsw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxgfwyf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhdfmer.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eybrciwd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jytsecer.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxmhvlp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gavkksrv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxwpydj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kajructi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nompgadm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vxenpqfm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zvleyand.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpihblxo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkdfjrm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hssilswu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqknknls.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqzywdm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqktlbnz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuofhfgn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2olzeqzql.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyecfxvv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fquidvjx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2iaehgvwf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kojqiplh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tlagwbcv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hqignhcf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2budkayqs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwulsgsv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkgmoha.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wacrralh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kovtqspe.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqikcoq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zecbudbg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxxvfiu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2igtizzwe.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aahzpurc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2febzzmsv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhntyjn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyzfvvy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqymftii.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtudziw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2knzkwawm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtouwhbg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2djvuidmi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoykmer.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dqshavyz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2laiottpm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ypisbovx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwdnhxt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2shqxhtoc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2esiuzaha.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdlxpzi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpphjsn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpbketp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvbhigq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sizzhhpt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdaenwy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vsypfehh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaljxfi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syzxsiiz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgoiosa.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eklvbvbq.html


<!-- 参考信息 -->