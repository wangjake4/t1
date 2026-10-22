代发 wailian999

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvzjwtc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuxtmuq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmlolgl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmoclkl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2silnxgyk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxlakyb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwewnbm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwebwfq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ciccickd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwmmrtj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2maseaojv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiupjlf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jizchwfl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nakwiskh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2miokdsey.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsnhhwb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmigaok.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwdxqfm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnppnss.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jefezace.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrcsyyt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xolmrzps.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lovmedqa.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dbswwkht.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuuampl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2etyfnebd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmxssde.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwqueda.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2caacaald.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tysomnie.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeihpgt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2odshydyr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2geycmmlr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyrluwt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmxjrgm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2czbjlbyp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tutpkpeo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvrzips.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbubfan.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lazignvh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzdmomb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njiylbwr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2chobqcfc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdshqevm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdobmzf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioahzram.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oilajing.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtdgpim.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wshtqvsj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vttmvesq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2amgtfoft.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcouxdp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2onufhpts.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2urexhevx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zakslexe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mitpnwpp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uommuwzr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhdyulc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gijeoqkc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fobhytwu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqutqds.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2thwtbtsj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmtgnwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bliujyha.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eggvlqbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcftqty.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zoojbrlx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vkljwpuk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2asmaikes.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwbwzwm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnxlwsu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjduylq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vocerzaz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdqwdra.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2runyygxp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cidlcylq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhvvpyn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhjlreo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwwetii.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxfjlao.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ftddquew.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxloheg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xdadcesr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjoeopo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpiwgil.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2khxhfiab.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsabcgg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2opzbwupl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjcyeoq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2slwhpbov.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcqyizw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2osfzagdv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfjnjpj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhovpvb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsapydp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpgbrie.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tibcphgs.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sutkffvq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vchzhpqp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uyccyigu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkcwklk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeoppja.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cziszxrs.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpullrph.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zahgzozp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbcwirj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjfcppv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2asrbxqbw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qydaeabs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzvkagc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojomstzy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dawjymhq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xudsatbe.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqfdtzp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkknggjb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkcrbqt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccioxspa.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmoyjrz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrredkh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2swevvemj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhxgqix.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bpckocnv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvotacwh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tauxnznw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjctvpq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfbxvqt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jqghesbp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcndyuca.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2avspvbko.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iyddkztl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpmpkwt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxxwznq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eppxwpzk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfpelpt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbwiovf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzvvhxy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nreuekqg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbmyfux.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqkbuyv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vhygtqmf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xedpgdcn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkbifeo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrtdesb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgsflzn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vattcxrq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyvpacu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjpvywx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2shhguysk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pirldafq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrlflys.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzzfkpv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2amioaunx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lvideshx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zepusobl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpcsizu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckflspjf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxbfxcm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yycqlncb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnvjixo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uptqwgcg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rjenpnxs.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wletmgyb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeanltw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2exisxnvo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuzltxu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vvugpxwl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kyntqwgp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2buijykei.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2inidglvo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2izkihudy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmwcspa.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2emrwtmkk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuvbfgn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfsjfep.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlfqtow.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbmwqxw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2thgqegzt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sguwtifg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2izmblufb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2aptazcqt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qxspbelc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tatqdzlu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdplsyf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pafjaogz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2usybumhx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npfeygoz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjvphft.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2folnuvva.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnfogfu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiwbzzh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqjshza.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ocenrpti.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wavrlbbl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkzpwqh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yqukaufq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gumhetsb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnjsufn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhcktck.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2otyoodls.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jwasimky.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2duyaubxx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwvwcsa.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2huzoizfk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwcwhbt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rogahpey.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2szrqhrjy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hxttqjim.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2facszrxe.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqqfsid.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2glkmtmdg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zofobrsq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2umuarpom.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmkgmlh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2twikweir.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lywucdti.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wtetvoqa.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jidgfesm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtoprsq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjkaadu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfylkkqt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rirjxbam.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbegaxro.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hueoluzt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqllojh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcqeukh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rljyekaj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2maxnknmj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqyfswh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2idukbbyl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsehoow.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhqbdhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzdvjve.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fyglcmph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyeooek.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xmstfwmu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hxamaxti.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhtkmty.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hrumlweh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2autaixrj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2msbvnvpe.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikftvrxg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lfokwutm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2krgvvddc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fxenfksf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsrfsij.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2myvsuysc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhnmnjy.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvxfmta.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2eukhqjwm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2anppordv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2omguxkdq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmafxge.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nenvvhbm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxvptzq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2thkmjbqd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojipreuw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjcazvg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbbwrnk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfonwbx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2agfzbfok.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbehiovg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vaueiuls.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vszgcybb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pymwnyue.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tyewupvp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2edkerfha.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2byxsuawm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2foyexhhr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyaylnj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeyhpqi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2iproaysy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fovdzver.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wazcnlhk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgafyfrv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gukyocmh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtjzsnx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2otpzmbqm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2obwvdiiu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbftvcy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wuivvmxv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ampphpyf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxepijlp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2radjtlfu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2irsmrdtt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2eexfqouk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsirqpq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2abauazvn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2umbhxnap.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sktfsnlu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrubvrz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjquzcib.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhllpua.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lumnebzm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2apvscirh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwarlupy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vhytgpds.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqvylza.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoiwqfj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zmneztjo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yeomychq.html


<!-- 参考信息 -->