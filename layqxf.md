代发 wailian999

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rshbjjvc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2guhowwlu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcnxfjv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvepgdlg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmtilyd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrvpqxv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxvhyio.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wocchmua.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrkyhhl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxrmvof.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jltqjujp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaazsib.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbbrmit.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzitace.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kaprfsjy.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzlfdtk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gubshmxa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjigfft.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2raacrbgz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnftrqr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvywzdu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjbvvmo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aguohljx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hneezczm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwrzqel.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqxvila.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zkobyiat.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjtzqgx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwvliia.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2evlsjfbn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jodhboyv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvsirgw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvbdvlf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlqyccw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ornwnwxt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txiimbao.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnhoyxj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rllwjrwd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmtswsi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbcewfe.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvftepe.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjstntzi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sauwbuyl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2goadtgsk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbqwwtx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnalvth.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2umnyllet.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2criwpjjs.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrhhqui.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcgnnsd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmihgkd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2udzkduaj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vqheazkt.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2brhgrlek.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyevxrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwfhgpz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rtorlfam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uboklmhl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtzicca.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ehubgyex.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvxkthd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwmwgpr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2swgyejyq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trvkhids.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhxxhhe.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2scabbgzl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tteaavao.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnipvmr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkuuanl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmugfum.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnwpcdc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fllqnilt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fndderma.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxxmbhs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoyzxlp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lcroxoqv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zixvvskf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2axbbifcg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkezbdd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjeddpr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmyeasv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2akccciqz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vipwufgw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iimmzkrd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wauxtgju.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyxngvd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxmxbar.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkbfgpc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnaywkz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yevflhud.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmysmzcf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsusfrxp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsylrbs.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdjbkpb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2scxamjge.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2oeapytgj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvrucou.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqwpefd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgsfxqg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxrydhe.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwseolno.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2geqvugwu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmaszuj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpidivb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggastmrj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vmijtqtr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2imwbhcbq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfbvxms.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjxfiva.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlrhktw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxuackv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkldckl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utawygwy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxvzjqf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2djrasimm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2giuvunnd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbynboe.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bhirwzfn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fruidheu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2intahbex.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlsqgic.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnykanq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfmyocg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zatchxtc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwujjwla.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2laocdcoy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poihlroe.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqpjdwk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmtedfx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkzgtfh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgvqxsq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2eshuwwtf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lftgivhy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzkeelz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2manjwpdi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pllbytqw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqitgtmn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uynkjleh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcofgpt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zflgvuul.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdjpiyz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpdweqj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jauejbsa.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrxhkic.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nvksrzys.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaivpye.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdgnlcy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jznjxqsd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mamzolgt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2adywmymg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbnbklq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sqicwmxf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jptnupis.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlmcbnx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkjmbsw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iknigkxo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wxieihhg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2irtzmtcm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yagxloup.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vofidyxo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfrfrho.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwrpcav.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyhenma.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bbghbkfg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2oocwprpl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lckvswok.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uydokmsv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyhseja.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wmodkbjo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvpnlka.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isryajqm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ipacptzc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dobrzjgj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqpvugb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dweldqyr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdzdulk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaxicwz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vimldqqi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxnlylj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fonohklu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iuknktwn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wsejmldh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2louebyac.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yviwifts.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lhclcdbe.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjfobyl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yweugvlg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgfyuuv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qgswxjos.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sytwhyha.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzupwpiu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2scifumzc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwulczx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbzlrqf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaagmkk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxduepey.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcuthol.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bquwbseh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sboxzncz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zcycpcde.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvhfyij.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrrbpkt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpmnzfz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2egaasfjf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nauvqmwl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgwdvqo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwpqsmx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2njrzfdbc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2poqwrgow.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjometg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqoixuw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvabuke.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kktrlnhr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izzgxxjt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2avgowovu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xeizowua.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xzatsfwg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ievaeulv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2miznugxb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jxljupzd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hroxljaj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxjwyxz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jzilryfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkbuqoz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmzstqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdofhwda.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2afpkgjtw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhvuszp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsshmue.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2andlulqd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcvvxxw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcabrmnr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrldnhkn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlptlob.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfateug.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmeumvi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2msxeiaan.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nabbbhst.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxrxiln.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2smvmjmim.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhixfbh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2eioougpd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vldrlnqr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rihrzjvk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zafeomak.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2eipfevdq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkqwawz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2viknqrnu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoupefj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxneohfo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2egasiwdy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cywuxyum.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyqdfqh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjhhewn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xttikfsc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nefotdja.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaxwgct.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sczzglvp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2grrvtudu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2szsmcytw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxsgveg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uegsyrxd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2btcchkcq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lszqzkhc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugudjdeq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kisqlwzn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikevdpcz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hytzblfp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2krnjfask.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2upmcwnrh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2potfpslo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsnyjzi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjszpjj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfloqkkz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnqfctx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2brzytzhg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2muygzwtn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlcmlxd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2objuguxd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcsgnmj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hymgkmta.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsklqmu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfuojrt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gacxtwkx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtjoety.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eockoujx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2saszvolc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyrjdnx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zykrwkfg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2escjygxh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mffnpgob.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpsptzf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsxooew.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeewxfom.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wiznmhpp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfgkvni.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwhxxzg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzchaqs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsmlloj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhugohv.html


<!-- 参考信息 -->