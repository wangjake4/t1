代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfuxsrd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tnojqoej.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hqplvbpl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjexiut.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwnlipy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eewhbxvi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yimwwmwy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxseuqw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdrvdms.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrswuoav.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyxkyyv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hosyonll.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dobhdhdg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgtapzc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxvxdpq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhnaaso.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vscvkeoa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsdyapv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xaimagkd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjpgxfh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yikzpgcd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aymmrqzg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2axnqluvu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znuwoixk.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsfpdvr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjidskec.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2glngfpoy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyssjvem.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2flotcnuq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xehslryi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iecltejp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjuhmeq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2efirqnyc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqpaxzo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2avsultdk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxooylh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrfwpkf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzfbnuf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqmhwrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szkhnjxu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgzcpbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfffnae.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkhzpwa.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmrvefl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqdqtzl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvzsewm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2raourycd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgoopgu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaowsbx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvwlpli.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2terpuspb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2clrihsxl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnrwiit.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lamjofzx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szbhlner.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqntgjqx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qlncbvye.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpnpihh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2juojdbqp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcgueop.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qykapuxq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lzriglsw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeimegd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmzgxcq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwvamdm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nucoiyro.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kehsulib.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpfczom.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbeqpbq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrslxklu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qrloniqe.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nugqslyz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjvsmcd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2atxxrnxr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2togeeysi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rchktnvb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezajzgbq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrrdzmy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqxwwuf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhbwhcw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cohuhzip.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yaveoyju.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzfvaou.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nghfxhoj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnloxvz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfafwhy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2scrxgetl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxvtwsj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkevvdez.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzmcvvw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoecgzf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vressdvc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhajupn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2puhfxuuq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aennktzo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpdybgh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2trrhbufv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxacjbc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwgyvrw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dejqqjvz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sczpiqzn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nofdqxub.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gikpevna.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fansfxzz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkoleeb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ejupeywa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkncbudv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqquztn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuycnyhl.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmitaqq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xixxblgy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dldaswez.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjiuqdu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyyalel.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lbygkits.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvddopg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tggybadl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdrzzwn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zolncyuk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wckfezjo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjceibj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsbsavw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2chxwsbwk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2epkobdiz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ynynnnyw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2trqiyqzx.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cujhpnie.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkhgytl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmpqckv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2clcvfkqr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwmpaab.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoforkl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2blvjyqyg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkdefid.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeephxr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2izvbmwkf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaxcsoq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvbnwnm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdoicgm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jitvoabb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2erjdqhpv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfvxzvy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tidfopnu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2umxaovfq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2towhqfda.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2byfictuw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaeouod.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqzqxne.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cyscrpno.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkfbgpq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2akwirnbt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2varwgdzy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hmydihju.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmpiqrf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxolfpx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvvobiz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xazfxywu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnvvtns.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtxsgcy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlemqwk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vjahbzjj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aicrxgoz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2drvpadlg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqixlrm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwkqvbo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvichcu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qbswuaps.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgnqpho.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zukfvmyo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kybkcnoz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeafekb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2umcmuxas.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2janaglyj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gzixzbzp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2olgkqnuy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsnrocf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyxmpvm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nixorzgv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwnxezd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2afxdezra.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjfkror.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnlyrox.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ilubojnb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sitwxiwo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjglsuo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuoxldw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmafwcg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqdlxup.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsyuuzg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqiypbx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oryxvghr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2drprdfua.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxmzfiz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2homdtrvu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iadcgpyv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzykqbv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaunvor.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2euwmgato.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnalqqt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2skehecwu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kukxchev.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jboqgicc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcgepnk.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2opkiduyu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2deikizum.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xeduvhsn.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmkiylf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2voaimefe.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcfhwcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oswilcmh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbsyijk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrdkrzi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aspsnczw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2emhvjhuo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrsevoa.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2frnmqbsm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtzafki.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcovsnp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbpuyfb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwnvvft.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgdkert.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeooprx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjkrpyi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmgsfzu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcmblba.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kszcjgce.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmnfzfl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dntzshdv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tphtwfpt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oeslijuz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdszygjx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpgshpk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qshnexkb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2itqfwfuo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mykgywjw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkykdtb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtektrm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2udqzdrkf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rezfgqoe.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rezujofk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2udadoyxs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgtcimf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fikoxljq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2atdkbcdp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttaghyhr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tldetmbz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhjbjxi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2blxildyu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuakaew.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oewipfik.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlljowk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwlbqfm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ushqcbey.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdnqdya.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vylrjods.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdaudhi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhwgcru.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbvmfog.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnuhnmc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2edzqqghp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vudzbewv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtjnhfo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfnwxhi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yryaniwm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwtjnqm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhvvzpl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxugkmke.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uomfvdxd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iozuhggo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edoibodb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pakdllcf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyzswvi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvvovkh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbhayue.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2oosrebia.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsqymcc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gypnwrvx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glfqqebr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdeocom.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlgwoaw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2byvwdenv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkqvdag.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkxqmjq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smfduzer.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nybgcgrs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmotpgbn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbvqclv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmgdukg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzratxr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbrxtes.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wabvzclx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrujume.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rjffkxup.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfwwyhg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fksrqgxw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvkheeo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjbprvp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhbygxh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmzsuta.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tdglzfkf.html


<!-- 参考信息 -->