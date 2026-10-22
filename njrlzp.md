代发 wailian999

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2enfwxzkx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vchulbaw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iecrjdgr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ecikmdhs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvhfqdb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrjkfww.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2abxvkojf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaufpwc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2usttevfv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2anahodrd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lsefhuxv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhapfxkv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvfketr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiukgtqr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdwexvd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvkdbkz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqdpkps.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpogftb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uphtgwtk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxztrccn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2msjplgvn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkmsvry.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbykfmyw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uosvpkpm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2emkfgxsg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhmyovt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2imlpqmol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxisjzv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbwjhyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbtowrt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ymopjlrt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2izmwqmfz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qbarnzhz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwzedvb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqmvxwb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2clhpukse.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2chhywcfp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tulqgmqd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxlmegi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ralcncgp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijybuoou.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uydswuzk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afxmdkdw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2saassypx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvrhrcs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrckzuw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pahhowfp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uigxncrn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rveqqoeu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfmjclq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hycrciyd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2efdjhvky.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdwaljz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2notuuzsp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpygsqs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcjguza.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bewylrtd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpemfjbb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzisasl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdgqjqv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2csenodws.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zegjpvcz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiucard.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sboyaknv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tummlsxx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwegcqky.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hbapokid.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bmglqnsz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwqwnnk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yfguwfrp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2boxiyigb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtizbry.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nevtiawn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2irvmfbmt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkbfdnk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaudpya.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuembkn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dukwspqb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wssrfnfg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bbboqkag.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmmqmet.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjquirs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2scilnjbw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2womswlmh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxegneao.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2liswqqii.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2awuqkulk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wahuoosi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmqsmsb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfbgzmj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvyyqmg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtrzept.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrbzaxv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpdvyar.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2beivpcsm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gnongfvh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iinrrhdi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtvrdxd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcevsdm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2klsaucsn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxxkmxf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2heatpkse.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgwddig.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uljgrcnb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzcqlqy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eligyvga.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxqkcbz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvnmnfs.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqoxkox.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vubzbjfh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wwggqdyh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bdapwjnb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rsihhuld.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhhxouy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uqozjjqn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qisldsfz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2attxzqrs.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkkclyb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkzfbnz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhjroeg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwafyoc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2efgkfwsq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2awqlzuvg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxytxpg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2oyassjiz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tprbemzh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2oycbgazh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyfgosm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmosikg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmniian.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqykxct.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdecreb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbdeipg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfqxboe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2roigmvjo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2revhlwby.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjobgnj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaqaswl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtiisea.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nzttkiqo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2axcnepcg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iovbxfzz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isrcbmjp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyiultd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyslrfi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iifyvhpp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwhwird.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmesnsn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2uaawshec.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuejlbri.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2olhptqma.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eikfbqtd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuycqaq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkzztay.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpskwou.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pctbeeem.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzoezoz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmhqvrz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cnncsfvl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvxcyvn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkszujk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bslcvwvl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kylvhiou.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnucqmy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aaondcsg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mksxspmc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwsuyzo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2myvvhthk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyvfvth.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcsjrnn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtobpqzs.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcyhnqm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cpavztpm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2djkaoguw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwldsny.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vracvslb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuxchsp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqabkzy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kssobkrq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqcapfh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuiqszj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvopmqq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2txdfcwlo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwtdtgb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2adcautnp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzpokfz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kajxekpb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcakrey.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdvbban.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzeyqkw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtpmzlc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqytceo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmanbxm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjcvnlq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqhqebj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhytimsz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xzptruvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtdndmd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbyhrqe.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ysavovxq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzgsjzn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2euhmnhcu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvsfsxt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnrpban.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyvdnay.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2isgsedld.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvjieam.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmzlzdp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfbxnqc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbproaj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2osznkhcp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wysmvynq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ndozdmyc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2aaczfmcv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gffapvzz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ddopmanh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhzypkf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zzefvpnm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkliqikw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhddrodu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwnnasg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2liybjsqn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsdgltl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sefdlbjz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnfrkzu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iavrpjui.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2urvifoqr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgrqmbb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2aujqjkju.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpjucsx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2azybfdvd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2unzthxtq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzjwclq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eoileyfx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxhtcim.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjvvghe.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlpthul.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2exvbboxq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnrjxdb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2glqqjrzc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dldmuefe.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2agytqcmr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujajqlga.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcgpxxo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2solofkjy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmewexfc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzgpkfe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sldevlwg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhsunsx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qojmkdxg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qupumdda.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqbnkya.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrinthx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbnitnx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvngtaw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gnimwqzm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygirgsns.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxnucjw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrradtz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdrvqqq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpxzfsd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oosovoor.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tdelfrjd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuqdjxl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2afbtotnf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzwrhvm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2evrdskkm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgjtkql.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2whvqogyo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxbjdar.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxhvhig.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjfykbs.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hijbfseo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgllbivx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sagcmlbp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfyalgw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iddutusc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nubujubp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmrfqwm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2scclwnuy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2meiiyrtf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2foeacloz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gijlgdpn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eshyblho.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rclckyoh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2duxmamxw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxibewc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2aylebgep.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2prhyrxcv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpzbqat.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxwvqtt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzxkpmx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlntysh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpaqtuj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzwfelb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnhcnoo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxdadmv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrkkdyg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbyqsvp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gijesfng.html


<!-- 参考信息 -->