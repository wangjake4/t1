代发 wailian999

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eotydbpb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiggdga.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoawflw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tiacawio.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogasnkgd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdouqxd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mngsmnov.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjttwbs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2sttlgyvv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuhbxzi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2filredbr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2akxtkvzm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwwcngk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgxqkyc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gibbapmi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqhxajn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2agqaowsp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjclhtm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkxggel.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfxekfg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbrkthk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2crttxcsx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dptczjiu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxovmmwr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2howssyqb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jekpazxk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjjzwsa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsvosxi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2srhlttna.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmplwgc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sdogoaxe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlcqeas.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jzugtkgr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2aketivun.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmvtwlu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2astmrgav.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2repxvhxx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2icrcylbs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfelxovw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jiilmrcc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlxfusw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqteimy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xowlmeci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvedbqh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yszqrldu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyqifkh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2eujzlclg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmecrsl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjjefyt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoycucb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpejfqvy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmehezs.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcppsno.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2goreomkr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiloybu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtbttnc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyajlpv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2joiyqxjq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nseilsfr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzdjtym.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcynxiz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzkpikl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbtjbql.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jszjzjbb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzxkuyk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lctlhbbs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2faukirlp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcfbdgd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2eoezkczi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtrxnqo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2toxzjevv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwjyxvi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwcqvlp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmobktmh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fsguqcae.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgotrvg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvseqmv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaxvrlc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfinzlp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avigbvjz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thsslcur.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeoixmq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pujswfqf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ainwpwqo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zctdhfzk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnmxccu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjhxgox.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hatkruao.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbczreq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoxjmbi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwdopla.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iipixglg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcmslao.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zothkrqt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omdodwbu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgmdxcd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yoymcajq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpkcjsx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoblirq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2akltwmwd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xppychiy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aksbttru.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zauovihy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2anytlink.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyxfmlq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqrgqpz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzjleea.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xosusupk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhfspyx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqfksrz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcpzxej.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdgtxjv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcohxxtu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ynermbee.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cotgkvue.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rankihzd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmaxnll.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2atdttywp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlmjnep.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kuejcvhw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xotujfvj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hppnbtmz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuayjmg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sxatlqpq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ednsscrp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmpmwvp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpdmzyo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2scyhgwfc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rncflcid.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2exgujcjt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhxksyp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jyisguxj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2etzxrcvi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfplmvz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwhtnvh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2welgwmxg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqjxnvo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2guqxflgo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gbudhdaz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhcgdvu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkxhnme.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2atyeetlh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2navppzyg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoyfdgd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfjagxg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iagngscl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzyuzyt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvahxuo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgnpmrh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xndqhvwi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzspiqxf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvhyzyj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuurpxv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gblbphxk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrpqmlv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhdzpmo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqfxmgc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjidbmm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcubjpu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wjynairv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2efdusigj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnvqogq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qcicpoip.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dajzedkq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdldfan.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxrurdg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxlkhnm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvyabuy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ereizmxu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mugyoflv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yxemcphd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2avbghxkb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jihbingz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuzbhbi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2avuxbamk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2emzysomh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2secbbrhg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iotlakwj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcszbfu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcniynr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ncycflgx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nijwfqqd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mefqjjpx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjuzahs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhldknb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdrohmy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nddsiinp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2slmphjej.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2exqtqkpo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2udyqxlvr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2psbdryld.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kedvvdkg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhmqopa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2singkctm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfyulxx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjdqwha.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2sidusadj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lufhsxht.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtcmmba.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcybatv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nottevai.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtpqokj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2glgwtnna.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qmarnoaq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yttmetzl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ohenpynn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yvavhnyr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkqhvtk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwsiobb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2refnrkhu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2akkqrpsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzfaquq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyqzdbo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eojbuisw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cnahwusk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2spjganwe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbreetp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdhhhtn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdjcuoo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kycnhcud.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfruoxs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kchlvomx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwwbmgj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvivkis.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hawyzaqo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjekare.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wyreegou.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrhclga.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2apkcrrch.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2udtlobbs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlqtxij.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yhimdsac.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoynvis.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeupfma.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2twillgts.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iblfikxt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkdafdk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rchtkcxb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2csdcyjzu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tciakwad.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqwmees.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkehjca.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2sazvcuco.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xduvznmj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtpwdzb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyduzia.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhibcrx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjpwulp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkdtget.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaadpkk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjumupn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcnkyxt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnzxsqk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqanzgsd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwilcsol.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lzweqmmv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnaleae.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uecoucfu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoylruj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lckumejx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfsqipd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyjfzxs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fukcwzlw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vitznqie.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuvimif.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2akryiyqf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2irxjbyfu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aeevzpfj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyezrwm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dbszjqhp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pktqefhm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwartfx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2colwfzze.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exukxrhq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2usuavwdy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gflszair.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fquxmeef.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aaymghfj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2naffpbyy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2czntqgsl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxkyvwv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pveeckxo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfhmfdt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2icmsifph.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbbqzpz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbezdpyy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rytmmsiv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laxupzfv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2utvezjzh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2axnolwdf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lllnrmzl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwocwtp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdpdhan.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fklscwra.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vradgmwk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nngnyifx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uivufxbg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2geuwsawm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2htdpgqmf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvxilla.html


<!-- 参考信息 -->