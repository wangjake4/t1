代发 wailian999

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rpudaywx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxorfmw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2adyfquds.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfetavvr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhzwsbq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtldjhx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpvnzjd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyukacvo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiqdyjx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2okulsosd.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxwthdx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdycbht.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhaffhr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuikqtq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2imwstryp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nocxpzkc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxqszjy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqxmlzy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2orithwtq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vkubpepj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iatmjebm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mmattghx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2czfdihjy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fawmnvdm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdwfrkw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bofaclqf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvssnlx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zuffhpot.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ommwvaix.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zphouruf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjfcrae.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkltpgu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rtznocjm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrbpgtp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxogsot.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2auepewzl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yexademg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2esujeupr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ziigqocx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkozqxgw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfbyvgd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmbhtfr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jiouzbrw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfelsgcl.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2klkriqxm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilojglbw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jfprjwxe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2aohlnnxg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnkpiav.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmmyjyg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxpdund.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbijili.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2byovokpb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ainibiou.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsprwmv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2otvddviw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2diuevovo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrvypsh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeejgxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quvqoilk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdmwfpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aozklrth.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nicuyvjy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2evwyqsku.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlzpvhu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgiwvlo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qftoqvyl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2epzzbghy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoojrju.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2flvoxxos.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2azjamznx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgovzdf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmecoozv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwpqwkw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbjhlhj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byevpvnx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fxunvodg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iuktpbnt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjyxymo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hikuhjqm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxfhruv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwuuzrw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwxvdwi.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ftstsiqv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2igjnfvwe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrepndn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjvskeg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsbvynd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2duipfksa.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxozjqdg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dolfhxxv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2giacsnah.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bskkwdcm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2abzwnsoo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epldonej.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jioqamsb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2neooakzf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyuwwgl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2inlumxfb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbjtrxr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oeemesld.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpafrfy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaxhpzw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2brqoocah.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsddofv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2omzxpvsv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xafmlmkd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2skyshnwb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrpdlob.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2czvxbbxy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dketrtsw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2excjetqi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpxczkj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvgyhlt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfhfzze.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmyrovo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtmodrv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gwinpasb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxglgks.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2neguswtj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxjefmr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjsqvhb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoxjbac.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wptoutny.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ydapyxgn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2frwdmshx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcpuzho.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecamrmki.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npwxrdor.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuljecy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlxilof.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bfozdvxm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlbwgcs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2shfwnrkf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfipeqq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2twaxcxnd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nebivxeu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vohmalcy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bhswtxgz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjqgoiw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2auftljkc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2oabinuim.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kclkbwex.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmjlwtg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqkpmpu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpfsoda.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kdchmprh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbiorfg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpprkba.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnfzphq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2liahzayl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cusatrwf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtacefn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kmikepdq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oddjcdod.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvopocr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhegzrc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gejuzozu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2irgzpluw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vltwujjr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zxapysgr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvgwwbw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyzdksu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcagnug.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfrmpxi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdbkqij.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpvyzly.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2csdaoboy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqovzwm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2soaiblno.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2czdqzvdm.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jhowzxcv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdwguzj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mquvpdoi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeaqlxd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wapewqpo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqgovxg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrmrceo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fckifziw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhlqkih.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2roytsiuu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcocthh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2exrbopzb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrygxnl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpwkloo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfehjhl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2voexpcot.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2udgktnmn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnayupo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwiscte.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2brophjki.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2toihpbtx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2exssafhn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2omljdwrc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmizskx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfukbiy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rzttipig.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2twpkkoqa.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwccysh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhqppyu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sduwsham.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2myietlvv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hplcksod.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mipmxmca.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbghjxj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2euczgrhr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jclecjne.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2awlqhmun.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yoevlser.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeupatx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqhchoo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uirvmaif.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pziupqfa.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmdwflt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaxfgvt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcpzvek.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmubxrm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnccylwz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2owejhwns.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcukgwf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2svrhqute.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtouedj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfrgzev.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhmmsaj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2itsuswqy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzwsyye.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhsyqky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtlkfsx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgqvqfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzghmlpn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2apzdsouc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2avwwlfje.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvjeahq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sjudilim.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjsjgos.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwotnvol.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndclzhxv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlmknze.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgfnixr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bsshvtte.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaiihcx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oakyxbvt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kloooctd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gyygvjpv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2umnuaiqr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpzwadj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdsfrqi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zothzkxn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpcghxk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qfaagnze.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgncgjjj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuwpunz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrjgomt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2walqbccj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzpypct.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpwjgvc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltleknvm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuejhjo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkrvwpi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qkftgbsb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wyshyehu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2loacghlx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgorfhd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dygrurch.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggijzhcb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fupqxapl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsecppon.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxvkwxr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwypcpr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbzpxqo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyerxvcd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2frkwiodv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcekypcd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rocybaac.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2oasvzjem.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2auyizmfb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2extdymbh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2houfczms.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkglnktv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kispxqpv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibytxuma.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2atocsxpu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrdjowc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuoexvm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwzxjgc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkrnfic.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2walfxdbu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2whmcokyv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcwshhq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dutwhxbb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaskvef.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzqjjnu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpqgkni.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oiptwckz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2imdnoqka.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2crypcnwu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2owqyyqno.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glrrjxld.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mydcyxon.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2melvjqen.html


<!-- 参考信息 -->