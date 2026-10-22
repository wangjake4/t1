代发 wailian999

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zovwbcvn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcdlgnt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuhubar.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tnozibwa.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbgcwhg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuydtid.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmldxbnr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgowfun.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpfaarx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2erjdjmkz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hiabuhzm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lulbjzzz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2blqhjrjp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtxovzs.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dnugpezo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcodjge.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gzubecay.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgyuecd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsdijrr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdrmtlc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzxuazl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnpvvqe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtoeeml.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2numkxfti.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyhdvlx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ngweoeho.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2blunygzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxwljkg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaerwbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrpyjfs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bihftvnb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvwakap.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvnwrrj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwihzdx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmslmya.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ugecogzj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rrobcyzw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcahhpa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfadnkdv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2okkaodrz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrruqrp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrnjqri.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqhexfq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mirvgffc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbqnfrq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2viwxryro.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcwvveo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bzspemsv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjsmcwd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhdiuha.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2djsojumn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfzjotc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzvdbfh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdvwfkx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iulompyo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpahgpi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2etqvkstv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbcmghg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqdfjeg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2werxnxbw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2thguxbqi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiyusii.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpkkxls.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrtgmad.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtmqzvd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2txfzwneq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ldipswyi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2piptwrnk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpfvudq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ionzitru.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiaszic.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2minaovil.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvawqew.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zawprhsv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdshswu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzhdvjd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qasuyuvj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2czjzqmnc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2snmitdun.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rodtzjtn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxjhzrj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvytdvd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2veyncfyq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxjicyh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcmcwpc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nvugcozb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrvftsg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2upkrxtmq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlzsegu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2syqkkbww.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2anxzmkyq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhnvsqp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gdipzodq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iaastlhu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfieuos.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvzyrhc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iejbnvkg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2puyhoetm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoypgzn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oirlzgoa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbinpak.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhkbkim.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2othgdvyw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rizudriu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxholkz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlsbuyp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxsnapc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpzribj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecatthqi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhunvby.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zfardalx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdnywwa.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnlhser.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2knygyjmf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbpwjkn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rfopkrpf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hpppbpfh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wayfcvra.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyntvpc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqvdnlr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2spndrseo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2armumyag.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoqojyb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfyfncw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuvisoa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fbelzydf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2raopreax.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2atpmvmix.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zztcanei.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xykklrbk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lqozwgkg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2avopraed.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzaujnn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gppniejf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmoxmoe.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmpqkyy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2trbhlmzr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2apehsblx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvloypd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hraknecs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsdzuch.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yclndslj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkhfhtr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlaxqmm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvfnsvi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sybtceco.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gvofjrbw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwxjcwl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2juxjsyxb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjpbide.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbovoke.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2coqclbva.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbdbnaz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mhivzwcg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2baxuwanm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sssdtjor.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfpujpc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmzwevn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2czaktpuv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qtexdifm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2odvkcfxd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxjckrs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkvqgmv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jygwzfis.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2icgyxjgw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlwjfnm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhncwwn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zotycswu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2iawmnwas.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tuawerbj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmylbvl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dcznhgul.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiiadxt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2acqzlkya.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkiabxm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kfysgclj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2twmnicid.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnsceac.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pdthtsge.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqluqzg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnjdqqs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyvgjjw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2scrhziir.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aolhqjim.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxqpoxx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2houpovjx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2birsvidl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2omkzracb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqqdxpg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ckytmpkw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgqnvth.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vsabukee.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2auaesloq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nozuvhyx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ahssmfwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfhirsy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2opfeduhr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yywltfqv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pykzrryx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyfqagn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oborxxvc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ptddhwtb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ennebxxj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuvqdrx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sskliugs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjcbzvo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhxbckm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ndufqwwp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcqovvt.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuswpce.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2reoljeqb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2joafebyu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2banrwyuk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xlguhstd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztphhvvm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fuleqobp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2buctxnbi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2potfpxet.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dboiigsa.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzrygsv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmcymwo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuzrzcw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpszkmue.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnhasmz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfegzsbm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqgohcx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwzfryx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kycnrvoy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxxzmip.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2efguqupu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2arysqyte.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqjzdan.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2myrkziba.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eutuwiej.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbffvco.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsqdmqo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2afacxzps.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lkifuszr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2blteqmqv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuighsh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzqdynw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvemefv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsvrppw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2epotoqdy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2okordojk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvytghcz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iufeekbx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxavbov.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2foudqept.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uendjphl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvbihjd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gfetmare.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2muteueun.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaapepg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxymffk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krkorkcr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjabolg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfhciah.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsenxuef.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qymsvdtp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2siaewjsi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kkczyaob.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2smfwszjx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2syisyleb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2husouxqu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxplzjqo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2auykspwl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrlufyh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcquhmh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnbdbvw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoscptz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdrgwrp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhhsgba.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oswpuwpq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fqulsafg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxotkmqs.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yakbevkk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2odsrenbc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fepvaolg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxkaoyb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsgscsg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hidvwlbu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqiplky.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjelgbb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvodmys.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxqvkut.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sacrfgpf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrobzxd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2asmgmrke.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxavsra.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xfagltwh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wipiriwz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdauxiw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbdkqqe.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2edhuxfnq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbegsgq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hnezmqoe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlqbffw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2soazfbcq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaraqoj.html


<!-- 参考信息 -->