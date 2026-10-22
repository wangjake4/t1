代发 wailian999

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bakqtcgo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2chhtdyhd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbtqegm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2scwtrrbj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2icwjnzmm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mysseuvm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvwzaxs.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkwitav.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfddxzs.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqblahg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmjlxwt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeylqrw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2awqhvsun.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzogapxz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2eecxsdox.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxnzkvj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggelfsmz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cbllyret.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2srlzbrsm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlismqk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwackojg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2puvxqygq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2irskijex.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fimfgufv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wndpiwzq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrhwrbf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nkefpbxf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtfpjaj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cxicxvxk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxgyrzi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pehrcqol.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcmajda.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmsumjy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjzckzt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgmamac.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwyixyr.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wmszpjjz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkpgqqj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qxphopmv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlvvwvr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkptmpn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqstuml.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsfzpjf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqybrtz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pywgregs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnlbdek.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkrxfuq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hduhfygv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2schjblpf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsqispr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cntbpkia.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqpmznc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ankehhaw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ruahhieq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mewhxxsp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxybysj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2abiydaus.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpvmdov.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aarfvxkn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2utrabvpz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tflwybpy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwnrnsw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzapniuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbgfozp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpgbixn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iynoqfec.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2eweajkrm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bogaphxr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hsedwlmd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqqbauu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xaskzmlj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nlslnfle.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxgfvnm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwagbcc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvcspuh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzpmpfe.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjorkwk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvvgakr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjmcsrn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlegfmz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kfesatzs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fckavvhw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaifden.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjfrozu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgscdph.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2apmsrfmd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2locckkrq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmdcbpp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zazorocr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhkawit.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2odpfrzjp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cllcuxcm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2unztwqqd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhmuecu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgjnbpu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmhynxy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbbwmem.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnazqxc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2stiunkxk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ithdxcun.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rcejzqwl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcczfiu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxxtdly.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdquxal.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2azmfsmji.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2djnyneoi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvdknfi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmymifh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxygrpd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gznzuuan.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjhfitn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xigpuubd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeyioey.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiinucp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvmmyxy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvxcfzx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqfeiip.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2abmmdjfm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwzxokm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbtazpg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwpejjc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbrdiym.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjqsnam.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vbemdvns.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaanspd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uezwjixi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2csjesfpg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwhcsax.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rszvenmu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcxwygv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuyzuwt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoaawit.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwahlas.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qvexqgri.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfetezb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiaxmjy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuszygl.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuptjiz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2foackiob.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gojjrfqn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2oebypcqz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlsttyu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfkimwh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qewjmqlk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdavxkq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lcylfaqa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hqndgtzk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnelqlv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsgczfi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvotbgl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbbtqrh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2udbuzwxg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xkshloan.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kiodowcc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqbukag.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxyphfw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqnpoiy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2brxqzqwq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhxpnla.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjjwoya.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2albghdrt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2advxuemd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2stbpqfqd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2envpvlrc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eegmjcvk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqercuab.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uphnjdyk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbyygxb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhvuzbd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbypwao.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ungvlxow.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xieubttd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xpigenju.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwctqux.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ncizpfgg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2udiwfbgw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2neqdwxcs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkwqako.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2npqwbaar.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vutsdmdq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2drmqkjvd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhmuphh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqadenp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmeacge.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2molnavvs.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sljbiaiy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2unolnseb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxjfinm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ohciklpt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mysuagod.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2amwsqmzz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ceauovfx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeoewzq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmxvtxe.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdxtskr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjhkoyu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbwgsof.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsrzluu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsfzyrs.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2meltovkv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhcajuv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wurpmogo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyxethv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnvllcn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuosexk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yynebduq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2penttzuf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfsvwbt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwwiprz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbwxzxl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfiqvac.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmrsyuc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2uadkxtgz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2drfwyijw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuzukgt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnjvhqo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzkfsec.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcsueuz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdrgltu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2duwdexsy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyigyac.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbpsgjb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjoocyc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zecwddjs.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qlivuzsv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoovxmc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vyiqmwhu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnxyqma.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gziwbbxa.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kldpluug.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfjmyvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btizqhxt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vvntxoqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wunzcqzt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvcsdqs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2aegaleho.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amcvjvvf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eqznyusk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nksqxjer.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyyqpab.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgjtndk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2agorzbes.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfogszoz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pchjlzvl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dajzanjf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2otejlmwm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwtmjcz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2natnvohf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjssxap.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvixfcf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlzhtnl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrzrgbo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnigdgi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfxsrhs.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2puovtrof.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeatyyt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2chpdoixv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfwnhrx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcislkqe.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blujmiwt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpkbbvi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkpcluu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlotbqa.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdyfpgo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrkprbb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2shoisjnv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vzasoevc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxvkucm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikphagaa.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cinptkrm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rckmlukf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuprbvh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqnjoup.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtncjhx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2avmuhpfk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uquzawyn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmeuknp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzbmvci.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxlutrf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eskxstug.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfewugc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiusnmx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2udchfrin.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wpihmqay.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2igrgureu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgynsfb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnsykxh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sexhcnhb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxcdwzw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2amsnoqkz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfofjzv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2omcqrjnm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyjminu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtxjsls.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwliyilk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qprvojpi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ouizyolq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxnmsvb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpelepy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dpehlibt.html


<!-- 参考信息 -->