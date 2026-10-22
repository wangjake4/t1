代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnoippk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdrmoiy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqinzhu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqybfbe.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tliafmkd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nbchzkbj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwnktsl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vavuxbsm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stgkrkui.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwsnnkk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2puewrjtr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbrncmn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmvgsxn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2odelzvuj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zyncyivl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sjclkrep.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjvrwmw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2flgdrcfp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtnfdpj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjmdscq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkovnqm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2recyejqd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ubazibqm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrhyabj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwjrvjw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtporzc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2idpavfxu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvbwfdg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2slbtuygh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcgcsij.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2psiyrdgm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmczrwcq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfvaezk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eafoeohq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzfjhih.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2icuuxglg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hnknqgar.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czqgajyq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mkobeyqp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gicertqj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlcblof.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2iikxvbbh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmvfiob.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjiafsr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtruonul.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhmyyfq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wezjmumz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wupkxdiq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtyljbo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2avyttvlh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2glmpkxfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtfqscf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2svlyxdju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2joaplpkx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmrnhig.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpnfddj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnhkpzb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlprllj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjfkclp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbzlzja.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2toyenmhn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2crpkwpfb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2leemrjvs.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hulnudjo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvohgnz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoyvpnc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nioidsvf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwlicob.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhkzayk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2htqasgxb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kpionbnp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmdkguy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dtogrsqj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qafnzjug.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uylrezdu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrtqcup.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kezuszhd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2efnbmmro.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmzdjhz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ensufxge.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzthufw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zklembiu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdzfcix.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2afrmppuc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ifufchhh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hevfskgf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zmabdpwt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htacurxg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkanpdj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2irhlwgee.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ewivtrqh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xayhqtpv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2srptnuus.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2veokplvb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hygiqusk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjdhhyw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcldbcm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2szvthygg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlkhrvx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoooxgg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsyzhxx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfjcuke.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrodngn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrioilef.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjyvnhr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2inmzdfjo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkicjsyf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwahali.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvepmdc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mimstoli.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lejvvcsb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2shfipkdo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oozdndhv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqfrjmr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnuukts.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2suingozm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaxzolm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpuixnc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgwilzf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxqqjzi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfktags.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zbctpyni.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqsdpfo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpojoyw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vicsmqaj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmnrklb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgxplfu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2negohqvd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvdrwqg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2adjxsjys.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmapkps.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sgparwhw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnmovgz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgknhyh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rtahqfbo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaasfcu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gebusadj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhhyfnl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2peosdptb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gndonwjk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyrswzm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xsocabth.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hltrnhlk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xywtccdn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwqdosc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyzbuds.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xvseoxpm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vexbpnno.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hzurliot.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgxgkrf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zidkzxcb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcnqkou.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhaanzh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaflbyw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nnphldrf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nznobqbx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaslizv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rvylqtuh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vubrrtex.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2flqcfrfc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2irrsulxp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uztwfylf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2quuzwjrb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlhhzec.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mhljgcab.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqgaebn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxfqxtp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyjlrza.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jmicymlz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dshvvjoo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2svmxhvin.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkgykmq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2juaygyls.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twlppghl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hbazalcp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jrupgomj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnynmfh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wnthsshk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqkneqk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2koaxjgae.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qaulptno.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywknpggt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvolhyo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2spckqpca.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfntzls.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2stkgzhnk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxcjhof.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tugtwwvz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yqodqfiw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoxdivv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtitbes.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiitfxy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxzkbpz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgkykfv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2khudhahz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2uoogilfo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmfkyni.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mcthiwsz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nszyuxcx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wygycxac.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2exzsulgq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2txdmczel.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyqzovc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwaltxp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2sleiosko.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hocwmerl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixewyxvi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2metgvebb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdbkarb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpmfvgk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhekjvx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vipkchhu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2iglctsfs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vhznxfsx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgeupxn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2eujktgsx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dduohxjk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnwjxjd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2sixfghps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dypjbfau.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzmwwii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pargfrrs.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqriryk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqcughp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrrlsjb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sximssye.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xccurjsj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kurgrzru.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2solanmwp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpmmfsq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfvhvaw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aevsxmro.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iablgjbm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgsston.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfcryqm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kmydgeoi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gouskrub.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gscxddyl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxdzanv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoqkvhf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mmidbukg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tqifsabt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iybxtehx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jukrantb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2coxjorgw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpysljo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2femakerp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrpxfjt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gojhbwus.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dluokfus.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxerfasx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdfdocj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bophjwjd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvntngc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xoruvkqd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2musvvxox.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cilywppt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddewydnz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2igbqwarm.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjcogdh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfyhhfp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2arpsyejn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtterxik.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bzybefgw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2glhaierf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2apczfbqd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvzppij.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyrazax.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2szdkqhlo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2biimxacz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoceipv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tnytlenu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vectkxfb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpxshnp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghagteia.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvmlrpg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcngbqr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfewojl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuwmglf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdsovzw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2amjsrary.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gftrfjur.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzmsfdc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2odlshxyj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2avbsertf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzrzmaq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzrzqfa.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzqxbqg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfzurvo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtftodm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gshvxaik.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpymtlh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrebyoc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnvujmx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jogonpro.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nspappxg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2aaypzuzi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqxrhdv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdrafbq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfzwvax.html


<!-- 参考信息 -->