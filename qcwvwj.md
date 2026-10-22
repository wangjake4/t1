代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2edhyvsln.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bronirqw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtljppi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhjnrdn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tspoowdn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqzcixq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tzglnnyc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlbwezr.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdwcrkk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkcyzhq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jprgniut.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeunvte.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcxrair.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgivswed.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rukbsovk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hckfyrkh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fuszogjg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xucautbo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dddahlcj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzulyqp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2giljhuto.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxltvdqn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2laroxvgd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkutcdls.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2eklnurmi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqtigmf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgyhbao.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewipnjuc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmtdkcw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wskxriud.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2usphphkl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2geqrkhfs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwavaqq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zopfvbmj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxusufc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eguqgxcw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtudlmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgefhboa.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbsbdrt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mkipcmrn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwaswzy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjddwfz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2civfjzzq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgskxgf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2chvzkycz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2homlllzt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2curfqnto.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxnxvlr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxzuqns.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdfkweo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiqhohi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qacrvdsc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpmtlqp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uezomxei.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmblshe.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnyxmfa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vcovhtnr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxpkmvc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcltefd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xowouitf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2btajzlmv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xldewdkn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2genyxhkw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmdrtmp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzhswej.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtevrwh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoqmyab.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cmixjktq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbnkqcx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2autrruof.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qiedeuds.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfxzsbt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2koapxwjz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqmqzcx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzkihfq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzacgvtp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrprpbo.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fckptgvk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhumjda.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pagphewm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozviieen.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftympvtg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjafpjjj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gatxzulr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kieadgrc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2laxhxvcp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtabykj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiklmqw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkqmsht.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2anxxzllr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlmssft.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nfumrumx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzvptqy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzqrmem.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2flgmwuwl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cubbpqeb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sikvhicx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2frwyfwuj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2edoyeady.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwhlyvb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ckylechu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpfjjil.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2huavcfgo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sefrdisc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfdkbug.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yehgsiss.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtswqpps.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsdgtsf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzrambd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcpwfhp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2levuvymg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2filnobqd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tleyiigx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sokwuuuj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rsshvcvs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lldnycjp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnshyeo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xukefout.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uvexixji.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbbzxky.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2blctauxi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hxccpkkj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlexcac.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzmvwmx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yrunusnx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbcawlo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ioswwifp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2scnsuxfa.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnbewbc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ooftmlec.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnrswoz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ayolbusd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2owlgkleu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hkveaipc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvuastq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsqjwau.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2roftkxde.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2icoeqpbg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xjljyxnq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpnfdpt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sepdiyep.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eokxpjca.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pupjbdxd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hjshbfos.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbnwarr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lklxfngc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdhvmxb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mzljmsqs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2glgcetay.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcnmvty.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aawulyml.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2azkhpwro.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgztazf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2srvvolny.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xljssftx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fphxpqgc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2onlopglu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbmvczh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2onnicico.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jemdhrim.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyhmjwy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ukovhvig.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2csvyjwqd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrbdzyw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2orelsrsy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdeyvig.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqooked.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgmusep.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuhxqbn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsndtro.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2txunborl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeutyft.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yasmpzms.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hgirhmfm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaofrcn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvbobum.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2epuitikg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2roxpmwex.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oythuzix.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfuvhzh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoboodt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gidbjfxy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxkkoxu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2watnwhfh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhhnpzt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rprycigc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2usycmvqs.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2trcibteb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuiamqh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgxmxfp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cyybztfl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsunbxp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgfiotz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hihadmys.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2drklieyu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjfdxlh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2marwtbft.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvdjyvq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvfztka.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jlihbnhi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtrizvt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdissuo.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dptcahae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wybeqojf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2skjygznp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zspwqnlj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2beivojbn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjnjgef.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnswkzl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmvdqjz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvuczag.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvxrbce.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrmfluw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dbedbzsw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fietcbke.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2augigeux.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbacobk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmbsqba.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tzateabh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yybvyddg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2axswftlc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oikychoi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqykalc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hrglpxgn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kuusivag.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lypgggay.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxepmmq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzjkdyr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqwvghy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbqtyay.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjhrndn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhqxnme.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkjuztj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lximmjjp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uazrfcbv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2awzivvec.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qblnoxcw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrwlzlg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yavzjipx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbvfvdl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpjpkhg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxbadny.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pybrolai.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2buqvvskj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpnnhgd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqcczuy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2latmshso.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ztukbcmq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycairgmb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2queorjeh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2iemypbgc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uimrgbgi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlamhmnq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bocbfgya.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2whanlyjd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmgiuvg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2umxpbktp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaadliq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkxzjwh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2youqkiqo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2loduvees.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbtyzcn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jasbaqyf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rldstnxo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yibrankr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmggxbu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pofovxxf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lvubardl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eiclaada.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcjwexm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bizaepwk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2javtjmvz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2retctsis.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrebuep.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpsduud.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjlbykx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pghuuxxl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsztmbnr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2trzwyewp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjgvtbo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2csdggbcl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaivkkj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmwevid.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hptzqyrs.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyhtmqo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvmyuyi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfhrumk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqdvbpl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2biliadln.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnwzbvw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cyruqaoj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2skotuzgo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktujeaql.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yitcgkop.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcmrdwt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdsgonb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfhwmry.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rghpufqc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2aluepsxw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orarrpwo.html


<!-- 参考信息 -->