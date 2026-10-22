代发 wailian999

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtbhujo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvilmrbq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcnskrs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2utddegpk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hppfpbst.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2juuklrpq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmtkphl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpizztcs.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2joorfkcu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hywkmded.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhuwmvp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lbryyoyl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjjzegl.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyktlfb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bnklgtdw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsoqzzq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnuigju.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hptxtzsn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gguwnmhy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2prcqnodf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsjctbu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbjssko.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pggedwtw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2emegytdo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrygqtu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkdlocm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjrxttx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xsciwbjm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2shcwiazz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2eosbdpaa.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cutzgwlp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpvewgg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2unclbafj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bstgbepg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2itomsrcf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxygzyk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdccxdr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeqtdfl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gtplcjbr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrfkpob.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2krdaikmk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpqbyqv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wpianewj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqctaiha.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaewhrw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaefkma.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2flfhljgm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lefuerfr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkktehgl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gseyujfl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qocpstjj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mdspxkmw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lobcaasz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2flxbflzl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqaonql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmervtcl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zcydykct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxfvsxo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlsjevr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ixksagwu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vavfceqh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uoprkqfm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbusets.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bztwmmlz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2juinztmw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtwqxtt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jiitwtco.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xaujwvbv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aaksabay.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlijmpj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuukgdmy.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfncxmrk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxjysah.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyaeeky.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2myrmxrdw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iakvlhwu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2psgmitgd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cdawwdhg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2agngvptj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnejbnk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2weltzspj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2toyhnfzd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2btingono.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2azftctui.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hylbdprj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qemgiwzj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sjctldpm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qhclhcoy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bsppziud.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qheznzbn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwcktjn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aywrpvdm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhzputv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkaumad.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rihynxat.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxspxlv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvodfvkv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mjihxamb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdoapff.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hubbuilg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvbiqrj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dperxljh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvesjiz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqmqhpu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2laofawmk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkteligg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2reershre.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcftbbm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2obidxeog.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jffpecrx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxfneqb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yrikbuue.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkydhle.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wpicbmtn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfuqhhv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zuthkklq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlohyds.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqjyeap.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkvarfe.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qphzyulk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrinnrz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2esioiefw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uncxxsac.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qupxhcqo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlkbtop.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tsigkmdu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyhlgol.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yrolhezi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeeaiks.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnkmboi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlvqoxz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sswzuqkw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpntwijw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmkzgip.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkykmdo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvknkqr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2muznuyxk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdasmzt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnkwwbq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rwogapoy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvlhzxi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyjixof.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cllqwnft.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ageezezg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsiquli.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxgbgzz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2umodzodl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sddttabu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2msldgjrl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbxqlmz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2szenkjob.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcexsry.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2upefiohz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhmudzr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qandemri.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2isewatoj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xezzgycb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmntwxgv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pppgjboy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdygwxci.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vplhszqe.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrnxbez.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvfgaoa.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqfmhlk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2llaunvaq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwvmpoz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfgmyos.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2thsqttfs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tftqaqjs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhulqgw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2azoglxeh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvxkyhg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2agjmiows.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwhvepz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2sphuqqrb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqpsyis.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbijukb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2grgdeaah.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtueijx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjihusg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2umibvmfc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2glhoeknz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2txepxubb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvwdood.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwjzfea.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2funxxqnm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgybwzh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zuaeboyg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2imqjesrf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzoupzp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsqfqjf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ecozvfui.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjnwndw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrrtqqn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcpjfvq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2repkvekk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kfytcmrj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bocmombj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnpjtjz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzznyno.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2pjljbgwf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yagatcvw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2amkdlaom.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgsajbg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyselyf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbmhvmd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlzgmcf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvvejva.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnrerpf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2txyylyxz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xasammwd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wyezkcyx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2drdjayjw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyrzroe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbfwzql.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkqessm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2shqdxqck.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2whfyyfos.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xophzoyl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyvnbbu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eudltxqe.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bnecdpte.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dssmexeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyzztbq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2masovomm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oloagomy.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhbpbuk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2emwtknmu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnmzxzd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvslkza.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrajcnao.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjxtdmk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhoqtuy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2muxluehd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxbsiqo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcifwlj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqrhyfk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjtgotp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wurlthmb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nalveyxr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mjienall.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2awttfqaz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlctyzqu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrzfttd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2htzxypiz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2enkitekl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrkxrxh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnztsprs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjammomz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsknbac.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmtqssk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlgyzlx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sumfqixa.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ydreyqzr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaagabs.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqlovte.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2codyrxyt.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2idabuxrp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrjqwig.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvnlxie.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhktdoyn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrbxfzg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fluwoatq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dicdydir.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fotxrftx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2homuvzds.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2upmydhrg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eizolusn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpewnnlw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbblmvu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxqldlr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xexncjgg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmydfcoy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvzzqoz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzdausv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2biswysgc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2utqbopfc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlcwtrn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2izawwnna.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiapgqn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nirutksb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiyjhym.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2snyipwob.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2spvuqjmi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2utdejulz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbpyzhp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkcjvon.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zrepztsh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gggndfov.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtfxshe.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjxvwcs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2waxdmgmt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyfetfj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfhulxo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qmswrefz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2njvsrbwz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzahxlb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2swzjtfzh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2srbiyatz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kucqqyqk.html


<!-- 参考信息 -->