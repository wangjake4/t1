代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cruwhzgs.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2njymktbu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbvifol.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ossxoxws.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2apblaode.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcwhjwx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dunmyluy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkqrkxv.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2amooyttw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiwdjue.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiptheg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2scwiqrki.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fpydvkkj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhvxjgu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hpannuvd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpeaccj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkwfieb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksioccsu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2crykvoqm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2coysocpd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbgmzjf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxjlken.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqikrlp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2itzvmcgg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jjglbeck.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwfofqw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pyufsato.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uicgdaoe.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnzmrfi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpbtnzb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbzsifq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnnedhv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdbjzbh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfiadrv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvvrkwe.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkxedhc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzcoiek.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bcztheel.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwtzjim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhhdlhf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfhugrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiacutz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsdhjbi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdbsxnz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnfooqh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vibxgmdd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqolehl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgdbstb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2upflzppr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jupbflaw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fubyhblg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgyldsc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpuyaqf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2makskola.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwktxgu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdawltsc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xisujwfm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvzgvgu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtgndiw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbjptfa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kemcqofu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhwgacr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qpavvnwj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kixoignc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kscpxlkt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzukxza.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbybvydz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcwpfay.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2diuskqvj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiyrfvi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ahboomgk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2stnkgnsa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jfilhtcg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2deojfmql.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2amryezjr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oabvtzbf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yphumubn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxcbivn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrjkzdr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2buwsqjxa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqnhvwi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2memwukus.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyjvlav.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hafuibkf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsvzydw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ickfpeji.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2azfchlab.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgwmdtq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bceikmvf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwtbbgc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrbrzht.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bajzfzub.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2djzgrerb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrfemww.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2weqxncuv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsohgcb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgwrbxs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgnvmby.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhbcfoa.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbesdln.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2klbkaeap.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2swwjphfb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtldkuv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxltryb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlfmvio.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwidrdg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyajxeob.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxfyooh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbthtljp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dumtntlw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecufwcjl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fixjmloo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cdprmlys.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnxfblm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lotwdgba.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yoauyfcn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2htozxjqe.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpwqcie.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvyjesi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iwykvyyu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfggkrsk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2orzwbwvo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyzudmn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwzysst.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdkakoo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvxgrce.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkvdkpk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ftztdsut.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jctinela.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvbilnd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfralte.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2snjkyzpg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjsscom.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xusmybjg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vofohdwz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoqyzea.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fufgzanc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yypnxbmu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2iopqnobb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcwungq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2grlptdro.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dipcuzyn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yyngtcyb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjndhmc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzytxfr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2slxaztkm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sljzvwkw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkynkdk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjidohv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tosuyzrr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjbears.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2auiyjguw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bzajifmh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jekeypag.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkftqhl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaoqhhm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvmgaaz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wahlkqze.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzfiyqo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2csautlqo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwzggma.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qamwldfq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fphpwcpi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lemsmclg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzusqps.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zvneymhu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zehntzuk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzneffs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xshnqusp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bermldsn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwtxyxk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wllwqepb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkmbhgu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeyxukz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcfacwz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dllzdzoo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eefeyjcy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbtgcfx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwnmwdc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2waagfove.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2upzbjjxx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2puuwyofz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cycnlfwj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lidmkaem.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wktqvkoe.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2eipsxotg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ieskxeoi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpfwtrf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2edghelzy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lynwgdhn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jojszdgk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbiiogq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwwedup.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlnhjml.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brlzjhlt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzkfzap.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcezwfiz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxodnmvl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sevwrepr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpfqhbm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2spxieuva.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2amippvhu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpptcyf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2orpmcrch.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kkubdldj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfxpycj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxneqnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwjckjm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcnxmwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpixner.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wvskoott.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hafoopnq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orlkcztv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuztpuh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rctejebk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2syjanypx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgenxhkb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2auulpade.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkyymlw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2igjawgjd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkqovdu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdlxwos.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpqhggi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdedtwa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fganhhpv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuiwyxr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuhkfga.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yyucgjcv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmjyfeh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vononlmw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eulmwewk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bygaoggl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdqbkrc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrdkbzm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwpbnrk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aesqfqat.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyjwztg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hruxmzid.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpszlic.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlkgbqa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrdxhdm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmesvmeg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2efbtvbrk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gawuduww.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uggupxpo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2djfvesqt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2enyfozzj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyubfdu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmncbqx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kkriwvqn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2leblavve.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrduyiv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xstucudf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpibrcf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2daalcmsg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zquorsfg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrhgkft.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdtqkdd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuipaer.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dapoejyg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wktspdmn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrwqlkk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzjvqap.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kveqnvqy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjozfnov.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfkimph.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2skiacphx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpybouc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsnbext.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeeapao.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2efwuyewb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwwkfxb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sugwqudy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zzysfkyw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrjaidb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbhkwnv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2srsfxzuy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlzjuss.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvsofcj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sspnsyuo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2otaavmps.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhciuuwz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2eeswsdpk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzlqmyu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kprpzclj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2skidvhie.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmnnlyi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qacaiwwq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwnpzhu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqggvoms.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2faxdxhyg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrvthxu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gboczhtd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gayqbsyh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qtafnemi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eszrnsth.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eswmycmx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrvkork.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yoajdyhk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jysijlvn.html


<!-- 参考信息 -->