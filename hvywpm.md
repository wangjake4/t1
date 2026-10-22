代发 wailian999

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfpstqc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xonmdsvg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wektnybz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfncplf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsqmlic.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfppdriz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fapntufg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2weajtxvy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvtybim.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2avszsatq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ozumvkxj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzftfrvx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2idzvgtdn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpqsrnl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2argxowig.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nemuyiiv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxajxzu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzmdyhz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jprgmocr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mfigoqdy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxafxjxg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvtlsfb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qswxwupy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ekacxgkv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2inwwfxyw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsqoptg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kashieap.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmevujs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uuthwvpm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsierqq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqqetci.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2syuwywqu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jrluevhj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbajpfg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgqhpgs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qcweencs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwygljf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2opllbmua.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrchfgn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcugntoc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsoitui.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmmnwom.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vurfgpuj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfonypau.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfxldmb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqokxqo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mjehcxkm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmdrgkf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2utqwkara.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrojsjb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cokuakzd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2brdbtprx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpkyryt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdfnbdy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fncqsoes.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyvaxws.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2unztxtdc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwjijea.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kobeertb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tboxxmbf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jsadorgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2waftyrsw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2unsmubgb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkuuotf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2napeerne.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qeumpyoh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzbdogy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdopbjzd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2libahhhx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rquqkuec.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qegejvax.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gcckvpzb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwovoqux.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzvcruq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erxqakiw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oesgvowy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mjunpycf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgecvxe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsqcnil.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ratmmgow.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2modiqcpg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2npwruszo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdwvkpf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcxpvuq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2carnkesb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2crgyzily.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ephebscq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2upeevqyq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2volsgvgh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khtxayqy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxenmjs.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeodxrg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sooerswp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyghyjj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdqzodi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hccicyht.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jovycjtc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgqpuqm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2drmvobka.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvdccwb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nczadapn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2retdrgyw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgwsloo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzpsktf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fexexyjd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2djbygyqj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqjrxoh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qttwfltk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuxybwd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zsftgsrs.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2crmnfjqh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpxwqyq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2swfbyhto.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2flbejjks.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aetonqkh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbbqqdh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtazytlb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vimbisyv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbgzfwc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjdrtko.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pszwqfkm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2myipwliu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xbswfbeh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xanbgaiu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2egunpsvl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjvfcjh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzutndyn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdmwqqk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbkookx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rvapcbqf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjuxiez.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2olfzbqbe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtlwcdl.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxbdqqd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfyhvzf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdzwhqc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzogucal.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfdwaqx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zytgizxo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2prpuiaqi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgifcwnd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdffybf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcizoqj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ydghzttn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wsktjvcq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcaunki.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vynogdsd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2koyanpcl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zodwtnib.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2npavyhwl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sxipysbt.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqebtpm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2roodlwmq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hfglbejw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yjglttwy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhshiyh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2khylalhj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yoonbmmi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jrygrmyj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqilzitf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pykzguun.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrstvfk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2msvietgo.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aioprrbm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hibqvgso.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpudexi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdwxovj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uskpzyka.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2edmqfnjh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2czgyvsye.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mfscwwaq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjhbpcb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2avdmumtf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2knmiwkkb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfultxk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhrennw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlbwzkz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzkltrg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2phytzqvd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2edpvbwoi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zywutzmr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjeynkz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2iuaimubw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2aubswzeh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rpotpelz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2apydhghn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2odiavcdv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2okoxbwwl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2laxvrmro.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xoontupq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hculfyut.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjxcmpn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxecuex.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2aeokjwvf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrbfxvs.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxhytsf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2afdrceyl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvidneq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vultfsmf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqghprsu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdcknqg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlghytir.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvrysgi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwclkdc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wejyuhhx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cokqagce.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gmorbsxi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tyalrsis.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjxxtov.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaimryq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2acezivhy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqnwnow.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ocweoexn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkcwlct.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qitrgcch.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2myzdbigh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2yefxflkq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2macwhuid.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mzatpmyy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtpjlpk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dqevsrkm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xkccunvq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqgcmfw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2egsarzgj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hyucpteg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmlmhdp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvfzdbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzylzca.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xgagikgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnfywdw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhswuim.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2voizjyzo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmiyumw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2urtxoxjq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcplmzyu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeoumez.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsvfbao.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcfmxee.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqwpvtb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrjfuln.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pquzjmeq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtryciw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvahczu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbmbxza.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2eiorhijc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fchjxppl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyixwjft.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hkujlyia.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2njiuagca.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmohrmm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vodlsfes.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwqovxd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtvynkf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iflihzdu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2prkfymgg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcspvgdq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkfrbry.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pahaibhu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoqwesu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oivjmdpi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdewuhj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dngvcinm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvhwecg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xjavymlu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2znzoxomg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwocbmi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vooysign.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaojwkr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcirojqg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yyumzkoz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eednnrbx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mesolmcz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2divugzbu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hnylsxle.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcwcvwo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fborkvdz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2oedsuyhu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkakvfm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsqvvek.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2daxktvyj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vchacuhw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzwjjrd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvcbfpz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzjvofm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtgdbvn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrtaege.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmjmpfm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdjgalw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlyhzna.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdhurdn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wftosnre.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hurzhqhd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuvvrep.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfwfarm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrtfkdn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgrywca.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2obbaurmq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmtqqbd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtwfnni.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxqocbk.html


<!-- 参考信息 -->