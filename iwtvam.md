代发 wailian999

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gtvdhfaahu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtyghbhost.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gtmwbnyomq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhengqikj.top/Article/details/gtatzkytcs.html

[Q78] 当前时间
来源：http://dali.smart0.xyz/Article/details/gtomyioulk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gtyooobdci.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtuuvdubta.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gtifgxslqh.html

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gtfegtrbuz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahsuaenc.html

[Q81] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gthgykossn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gtmxzximij.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gtciirkrlx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtncizoeuh.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtzlicsbxf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtqocdrclt.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gtejuvuqfm.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtypavkysg.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gtojwwnigh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gtgiuqcguc.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gtlrrcbqge.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwswusfr.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoemyceq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gtdnxdsswc.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gtlwungsiw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gaohongyu789.top/Article/details/gtwpahpnoo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gtnmkpdxgy.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gtaywlwfog.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gtxvpejkee.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtpazptaqx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gtyftdorbz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcapcuzfq.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gtfzarfgwk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbsergzkb.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gtkbzzwlis.html

#!/usr/bin/env bash
来源：http://dali.pengpengdd.cyou/Article/details/gtuvtcrgkb.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gtyiicsujp.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gtjyckpxkc.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gtuyarcsha.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gtydvanjsx.html

readonly PI=3.14
来源：http://dali.gogol.net.cn/Article/details/gtbjvvizda.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gtrdqdrfhy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gtmqubexsf.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpojilkh.html

name="${1:-default}"
来源：http://dali.gotoacloud.top/Article/details/gtwpuekcxu.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gttiaizhww.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtkrhykyya.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtaqoolvae.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gtbwxbawfz.html

[R08] 数值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqzlfjxw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cqqwz.cn/Article/details/gtbcdirtdj.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtrsbffdyu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gtbpnjxgcu.html

[R10] 正则匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtlzgghbsi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gtgnkjtvps.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gtuniguctt.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gtldmszdfy.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtpcdddzfa.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gtypedkjtm.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gtdzldgjtb.html

esac
来源：http://dali.cqqwz.cn/Article/details/gtothdsyxm.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gtitjzxrhp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtuhrbrwzr.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtzvoqkbmp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtrstsgixw.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gtnbirvhfl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtuxdfzvcu.html

[R15] while 逐行读文件
来源：http://dali.yj20258.top/Article/details/gtaivtydzi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gtkiwswdta.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtpssnmwvj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtxnxxijcg.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gtlaiyyovr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gthwdlkyrb.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtdgzewxrn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gtbzghsskx.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtyufvndbe.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gtggysgyda.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gtkvuiuiqp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gthqsehult.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gttiejlixc.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gteqeplvrq.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtfgskafwi.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtrennggoy.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtjlvhfemb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtsplzscsw.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtcdsyzipo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gtvqiutxmk.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gthjfgwnjs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtwelzqlsb.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gttjpbojrr.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtkefaugfg.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtxgooxdlq.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkylieujf.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gtmclxhojb.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gtpoythybv.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtgxgyvfzz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtvokltwuz.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtnkrbrqjd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gtjsbxwlkx.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gtwetrzirk.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzcwdshla.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtofzhotkr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtnbynffoy.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtmdmgbeua.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gtynezovpu.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gtcmuaixjw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtlzanifsg.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gtcmovfozg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gtisonjvlt.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gtrjnyawto.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtxlvjvinc.html

[R37] 把输出赋给变量
来源：http://dali.xinyue.icu/Article/details/gtxxjiaqfs.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gtssenaksa.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gtpwtjnuyz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gtqyncjjxq.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtbkozhioo.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gtkeuzgvcn.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtiallipln.html

echo "log" >> out.log
来源：http://dali.kuanghao11.cn/Article/details/gtweaqgtmk.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gtlmktndhj.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtnwiempbz.html

[R42] 输入重定向
来源：http://dali.jinghuilouyu.cn/Article/details/gterfvoega.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gtbpnkxazk.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtmpmliajb.html

find . -name "*.log" -type f
来源：http://dali.zdqjudy.top/Article/details/gtiiwxggav.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gtjswdsnoz.html

find . -mtime -7 -type f
来源：http://dali.zhengqikj.top/Article/details/gtrdswquys.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhszmveh.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gtnqyknhoo.html

[R46] 递归替换文件内容
来源：http://dali.jqgufenzy.top/Article/details/gtutjhqtdf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gtfgqmdqvi.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gtosgppcvj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtmvrbbnho.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtzrlgxwfm.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtwzhjuaqt.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gttudwgcdw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gtkeuesrrt.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gtvfazxtmf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtescfwcpn.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtnjqobkgi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gtfhvtefbh.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtcgqtfrxy.html

wc -l a.txt
来源：http://dali.nwbrower.top/Article/details/gtchkedrpr.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gtfazagice.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtafovnwpt.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gtzafzaqtd.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gtqkadbuxp.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gttgmhinua.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsdqkppx.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtqfdqnsql.html

scp file user@host:/path/
来源：http://dali.iojbl.cn/Article/details/gtbttxtqmt.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gtmbtbywxf.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gtnwrvaeif.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjbmchtat.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gttbrmweqd.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirwwzddj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuxming.cn/Article/details/gtwcmineal.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtajahgkcl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gtvgkkpuol.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gtusmmmcvi.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gtirwcmzml.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gtggpabiyq.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gtiozmvjpj.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gtzclisuoo.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gtihhzttvv.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gtmjexbaax.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxywlkjhm.html

[R65] 查看端口占用
来源：http://dali.jianghu66.top/Article/details/gtkgjvptzc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gtsgnudgga.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gtmijvynep.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gtyosimewf.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gtebiugcku.html

openssl rand -hex 16
来源：http://dali.zhoulong.xyz/Article/details/gtcmdclofb.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gtxituxdhy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gtmygvntdw.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gtuswfoqqn.html

head -c 16 /dev/urandom | base64
来源：http://dali.yueranfly.top/Article/details/gtafpffqqy.html

[R70] 时间戳与互转
来源：http://dali.yueranfly.top/Article/details/gtajjycfzl.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtfmeqizbu.html

[R71] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtubaowbeh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gtkrwrynjr.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gtdznnmrgx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtcemllphh.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gttztfrncn.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gtjmhvsviq.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gthptqluxb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gtccmsmqlf.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gtzfpldrfr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtifekfgrv.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtpmpodemx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtddnizoet.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gttoeybfhb.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gtegqvzzum.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gtdtjheqpu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtxupmzasd.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtuxkhxfji.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxinkj.top/Article/details/gtzghfaxph.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gtstmaudon.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gtwcevnrup.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvirmqegq.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gtbbjdbvcx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtyazyilhn.html

[S01] C：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtxaicuiea.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gtjbcdguft.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.c1oappe.top/Article/details/gtujoqnvxg.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gtflolalju.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gthimixyhu.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gtmacacxwd.html

int x; scanf("%d", &x);
来源：http://dali.sweek.top/Article/details/gtokaxvrgb.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gteevekarz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtnjrhianu.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gtgdtygqdo.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gtjkstwemz.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktapdadq.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gttnnefkfw.html

[S07] C：数组遍历求和
来源：http://dali.iojbl.cn/Article/details/gtvjagcktc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtjndxlnyo.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtoqhsgelb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gtvviyzjui.html

[S09] C：结构体定义与初始化
来源：http://dali.jyoumei.cn/Article/details/gtdwnmqwws.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtnevrqllp.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gttqioclox.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtaxzsvixn.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtsagrptgb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gtmvusihmq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gteybnbhwz.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtqwjfjeic.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gtoklfjiuo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtgnaaxaqx.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gtqfaqrvfe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yonumen.top/Article/details/gtgvwkemqw.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gtyunffcyk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sweek.top/Article/details/gtabovtrvx.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtpkddkuff.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtyxaxkpve.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gtqffeawuz.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtygcfyebi.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtpnondyhh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tian-w.cn/Article/details/gtywuslpis.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gthhtbelbd.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gtciclksfq.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gtfwjrwbrt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtdrzyfkpz.html

[S20] C：二分查找
来源：http://dali.jqgufenzy.top/Article/details/gtymqdctvn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidpselyq.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gtgwhslzbh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gtmbzkjhyj.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtvqwopcol.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gtxbeenepi.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gtedtcijlh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gtxifwecck.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtupiymx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gtrxlrwlne.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtgvmcygus.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtnhgqnmxy.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gtucerseap.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gtlnnwpntf.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdnzczag.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtjgmirmve.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gtslzoucik.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtuyutxeew.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gtbhwxeeuz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gttltnauou.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gttybuypji.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtccavubgn.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtubwvxkia.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gtbkwcjohj.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtvcncsggo.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gtwwcwxzlg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gtokyczsnp.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwctymupv.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gtesinygsg.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gtrhbberaj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gtnwgashfj.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtalmsbdve.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtepsewhiu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gtfxbjllfc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtznlygdhm.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gtdbxrtxqg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtkybtfcca.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gtevksbacg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtpnklrdwf.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gtayssdhls.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gtbwcnjlmj.html

[S39] C++：自定义比较器排序
来源：http://dali.ppjwa.cn/Article/details/gtjpycnosd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gthiuzsnor.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gtehurojjf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gtrylbzphr.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gtflimkxpd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gtykqvdznc.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gtsriayebw.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gtcidpfmul.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtatimcwxz.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gtqiqrsuii.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gtsdcafutq.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gtqvuqheyb.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gtwljphrdj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gtdvhhbeho.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gteytqopgw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtizbxtihx.html


<!-- 参考信息 -->