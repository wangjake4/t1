代发 wailian999

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpzgzpk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fglkljio.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wytxieop.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkdsjwi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfparyy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsotzxu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvckzlv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2evfvnikb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfqbvxl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyeerar.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qixjlfvl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mufwerdc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsyaesx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2esafxuwh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ammmxbwu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qzywdops.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgkauvf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmbxrqg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fyobamls.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkopqwl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hlivyeqe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtbhhcr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhotikq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvneety.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oqptnslg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfageqyw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cztilklv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfadvpke.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2urjgqjdk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgqbipz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcovmlu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzwntxv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lslhtdgc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hiulmhqh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcdovqd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2yletoqtj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjktjjo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bfiirgqa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxznrcl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdgbilf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2drxbeuun.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2otsfkmek.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2syqkqvec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuhswxx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zoumtxfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfakbbbf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2caqybgnr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xijgjjcc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvotyjp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgfvsvo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyqnmtd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zglbzoyk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2usmvhome.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjyxecx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hivlblih.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2frtzswlx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfkhpcz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rfikuqol.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzauikir.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kitorlyg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gldhduxc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ktomsmud.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2woyvukrf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqjufhl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsvhxse.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaoqlzx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iwshsglm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2iavwyavd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qetppkhn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbntiyid.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjyzzmm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiukwdli.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrzbulb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lneqbvfs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lfenbxlg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmlfmri.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiunuua.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2psorsbas.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvevudp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttheglqf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpidvvp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyoxcdb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdfwkff.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yadesmjd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtypqqh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jftqevxh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2edpeqvxp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqrykzc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2itfftzly.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbfldgn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2htsmmpjw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ykobajss.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aavudzwj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwwzady.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcposjfa.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2soezunii.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbsqjig.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnjiuxo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjuovau.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfmjlcx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kicrprhl.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kygwmnhl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tidvwcii.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2twmbyonh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgikyimk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oohndejh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2eepgrqsq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aomkemrd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqvomqh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtvjudb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2aovubykj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ktehbewx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lefgygem.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bshbafki.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loonfgzf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmkvdgn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yujdmcub.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpzqdsz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jznbhaba.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbuisjj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lppofttv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpvcycr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiujoem.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pnutttyd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlychel.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwquyii.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhxpvfb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwovoga.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gutarxiv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sdejjhng.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uybtngpj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cbphyqpj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsubtdk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fxutvxxp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvyyafy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulotjlce.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tprcflnt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2blvnhjtb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uretthhd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gpalkoug.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyivslx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2avzgpyqi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxyvizo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvfputb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2siwkpbkg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhtaafm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdywbxp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gahxzqpx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2teusvuqm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyrpklt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvyeryi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyyigrq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2okdapjjj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2iuetkbgy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bncdmiao.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2swqgilzf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkrdguw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiiaefr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2smtklkap.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqrdkhv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pthndzel.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkrrvjm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2iryfcocf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cqynebll.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ietdxobm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgsodyz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2goncbukp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrzijzw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxzcyjt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvmmaof.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdmdpjy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2munlxqfl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxiujmf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jaitylbo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qphhpvoj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkoebou.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2eexovacm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2faxbmqzd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcjfrap.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvucnmo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzbvhzj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfmfkqn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmhxmld.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ovalwdcg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyxiixj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yssgajzr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpqvqpo.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jawhywxv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgtdmup.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uffnvgba.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuepzok.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2chhsamix.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtynijit.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjcubfj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mlngcbca.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zwutetyc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2eulffftu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ivelaaiv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtqmryw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gultendf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nscjqrnf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwvbczi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqlphhk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mquhcnbz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhlckzk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dthnyzoe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxshtop.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqondtd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmoxnuj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fbslpour.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgdsrur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzskvkg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dszyfmdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzwylyz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkizwefy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wedcodld.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vktpqqal.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2stotfnft.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnarpwvq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjigapy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cknhaxql.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bihferoc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oztcyfco.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkosneg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lytfyxnz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2drtjtsfo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhgrnpd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzvdbfi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2doqyydfg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pluayqcj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhpvqtj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pdisjllu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pdonaknd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqvdinz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2helrfosc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyupvvzr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkabdnuo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcknljjq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvaurqv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyvuhoh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmilkdc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hpimjnxd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvsnaky.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhfyufq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2exwniius.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2citcyadn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hlotezqr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gffxdufr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2atqcckgh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gobkbpqb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlagzsr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysibzizj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rexgeacf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mmppnbdv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aerunfdc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2deqoobaq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcnizss.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjmnqnp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcuiqzb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdjckxh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcpnujs.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoqiypv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xitlamhi.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeealwo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2axvbtoom.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2unwtoxua.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pegbtggo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkfapsf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zajdcvku.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlpqnyp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxiuvhn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aogthxaf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeiyaie.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjthfcrj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbzezpe.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjwwddi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgwniqb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jptdoypc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2blbomvps.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2niblhtmq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qeshzivo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edrecakx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgdgrgk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyieofcb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2eglwxnwn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2caxbbmye.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nitfrkhr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfljiqfp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vypvysfq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uekhhkch.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2baxnetsi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvuqqdl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cybferth.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgzqron.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcowrhb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgtuhhi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ipomxvzm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kanhfooo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hilfeptx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhirqph.html


<!-- 参考信息 -->