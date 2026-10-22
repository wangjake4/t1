代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcleplg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bdamtqbz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgobtjon.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyvbjwt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ashnjclq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fosaosgo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uoanrbes.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzofgme.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kaitvltc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2reeqanmy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvaffqu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2luiioowe.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlckqtd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuofawe.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rixnrvtp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtctykw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbayaxy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqukbpxj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dklzdnva.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxohcnty.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcmpbky.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jplllqnx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tbymtmef.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2aernagpg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dudlrwbs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgjwerq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hazzafbj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuhfvtl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgstigto.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvxpray.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkdbhnw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mockwpsc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wydwykgz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbpyzwm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntblhwhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdrdvwc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jveetsfe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czsooqzs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qerhexrf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wyybbgdi.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqseopr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lryimtyc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdfnqqv.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2extavedi.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdapnmn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvssply.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zughwnca.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmfhtjj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fikoyvis.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oshyicvi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwdyiyr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxcwefc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnlakml.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lbthlovx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyzgbtl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiykajp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yptzgkdu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hszflsdo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbuseff.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvcsyxg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgnebsj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxgiejv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkusuax.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqezzfaa.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhwkanh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2viwkwdyb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlmfyky.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtaldps.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aullcnzl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2huyhfkqn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njdcrorv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdulxxgl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2emrnfoum.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zknbjjhe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyxtabh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2viawkefm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzhlleg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2npmtlnvr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnppyzm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmxffwd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rshwfyic.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kltwcoos.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xggfpyhp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gedcmdpv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iznsmnpn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhlfsog.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2loexzbkw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuokqgd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oaftvthh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wewxtzgf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cegrqkds.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtpycal.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzjchqm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fawvzmuq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2klwcjcdx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jayzxnju.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfozoec.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqcrvne.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsgmaar.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sclngybs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnfxcfq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2atheaeaa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqblwpkh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtznfmf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azhtcqqt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2suugsrye.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtsxgeu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmuqamj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmpwjrh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2slpsadsw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkoejxs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyigfia.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wknbnljo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2udtluisf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mdieenvy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vusmlict.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fegevmke.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxftmvb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2apxuofeh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2drfagxjc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjnhizs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qzystsdy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xttvfcyr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dambsqzn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkpnckm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vawsyysp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gacguhqv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhzcqgm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fccqcnls.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2duxjrlxd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsbcppk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhutjyy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgxazyq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bmykoaxp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrsndwe.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwxckwl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqrbchc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcskprm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwaaoii.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yovivvji.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzbqszk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxlfmjn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qqghcjrz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mpinegwc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxtyaqt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjejhwu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrwnoct.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhtllwy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsrmyrn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmavrdxs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnoneiz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zloeeduf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2neauiglm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2khvqmujz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rksasumn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjkpaqn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vridcqcc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfwbiyq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2riccqltt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqavlys.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xsydnqnc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcwjkql.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxqarei.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpltmzf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2amfgfbdk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlulvmou.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyiubjz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gajgmkya.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2atcsvvip.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhgyfbp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnlqiwy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pivfxyvn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbcmblr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ggspnqis.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjibjpm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2llsloxto.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzbmfuy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqtqzah.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2niwcqgxz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qckthnqo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wktgvgnt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kktszrot.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2aofidzmn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2djftocfl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2afrgcskd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ehghxprl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgqnngb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cusdilge.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyutktp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgmmrpn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hfywcjeb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnclrwfz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqthert.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxgfiyv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjzivje.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ojityuie.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uglgpsyx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2bwivtygr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2edltvike.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvrfivh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnrbjyr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2evrzxtwx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2sslvmokm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuuphqc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmnsczp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kifssmdg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvhirkm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlknkzm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjlpwdz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nntulurj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuxxoru.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ceacefkw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2egponstj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gegtiorz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwcubaj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgqaegy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2etsyzxfk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfihcgb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwkgauq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ymebtoti.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgycehi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvswdpf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrymydkl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdwxnjk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqlohol.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kyydqovw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wovhltov.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvpeoai.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2orsclsmi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ornquxum.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zifkztkh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmpwnmz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbaponq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vowdatom.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhlzdcp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wlifmjod.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwpldxh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijswmqrd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ruikhduv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfxlcpf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjsfmqk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaxusgb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2phxcfozu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bumehcfz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmypbegu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aheuhgiu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixysbrcv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mcemdkrp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsazzwil.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dosfrsyv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuutoxjf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2inylchpc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwmgsmp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyagwvj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzjqyoq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zucmblgl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uokmrptu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nsspoqdf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfztxjlg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pgevbmzy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldymgqdu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfoxfxz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlknhtcy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkupmvd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bndlahlk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbeeyvw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bldkzsbr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuiauvj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ruveygdt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfioril.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyhyoqn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2omvryvni.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lfroylnn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaamkcu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jvztytjp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnmiuwf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2apoqekhx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdishmsm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxvasjw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qijjahnm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dooyvgvj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uypunqxv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nztigrhi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2llmrsxjy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbuyucx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2npnsboqe.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkgdsna.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rigzyyor.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2btuqwbyr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2sehtykmk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2episkftw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwclhqlz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxaxatf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtaulnx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlebzwz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2phycnpwz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfvkfjz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoupnqd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhtvkkv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skvmwvby.html


<!-- 参考信息 -->