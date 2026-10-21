代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gtfbzajjlq.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gtcyxfvent.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gtqtbdydvz.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtpvqlrdfw.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gtgritrfpj.html

[Q71] 查看建表语句
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiyoglpy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gttuydoxhc.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyujyoud.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gtqwnauzyb.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gtqinvkqjk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.haohaochexian.top/Article/details/gtbhitwnre.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gtjxtggkyy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gtqvzitzqq.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtvablwuly.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtiqffpcve.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hywenlv.cn/Article/details/gtimxnxlas.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gtmrrdcwoe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhixingplan.top/Article/details/gtuoaxtynh.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gtxykajpax.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gtvuryddox.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gteciftvkz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gtipvfkzie.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtbhbsohsk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtshftgbid.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtiqhiwayu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtqsevfdzo.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtonjaeaor.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tian-w.cn/Article/details/gtccofeist.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gtcrvyqyut.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtnfglqess.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtznmelfsq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtrrpoupbv.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gtcatljsvs.html

SELECT TRIM(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtxqrssdpy.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtpiissswp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtxieelkbz.html

[Q86] 读取 JSON 字段
来源：http://dali.hfpthk.cn/Article/details/gtnhozqmfm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtsmqrvgrv.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsazidjnl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gtskojqicj.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gtinovotyt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.c1oappe.top/Article/details/gtyqiobtvz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gtxklfgzze.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gtdklpnkza.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gtzglonevv.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtrfbxzbkc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtdejqrqdu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtcktapycf.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gtwjlismzb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzebnxwsl.html

[R01] shebang 与严格模式
来源：http://dali.jqgfzy.top/Article/details/gtitjeenga.html

#!/usr/bin/env bash
来源：http://dali.hfpthk.cn/Article/details/gtngjjabid.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnxrgnrp.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gtcrrwctmf.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gtwfvipsde.html

[R03] 只读变量
来源：http://dali.shanyushiyangtech.top/Article/details/gthbcllluq.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtcbyenowu.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtwyzbskft.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gtzqtpwstp.html

[R05] 参数默认值
来源：http://dali.daria6918.cn/Article/details/gtviyqptbi.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gtsorcddwq.html

[R06] 判断命令是否存在
来源：http://dali.c1oappe.top/Article/details/gtidyfcoio.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtbreckoha.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gtmntjerjl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtncfvplyn.html

[R08] 数值比较
来源：http://dali.nanxinkj.top/Article/details/gtpnkupeqo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenzaomai.com/Article/details/gtbeykwnhf.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtqaamtxcf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gtzyihcofe.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtuxqfstfi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gthwbasuob.html

[R11] case 多分支
来源：http://dali.zdqjudy.top/Article/details/gtxmbdxnat.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfnfmhpj.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gtjjagsscd.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gtmnhybnli.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gtpwnlyodu.html

esac
来源：http://dali.pycfn.com/Article/details/gtyrrtwsff.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtohpxnqko.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gtfewhvian.html

[R13] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gtyhnqkuyr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtfkwbjqgc.html

[R14] C 风格 for
来源：http://dali.chenlongwang.top/Article/details/gtluyddnjf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtyfrdpvxi.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtobmeisry.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtmjxcypsf.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gtxoxdkpdy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtpfziqtyz.html

[R17] 数组定义与取值
来源：http://dali.pengpengdd.cyou/Article/details/gtszgfxsvy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gtqzpyjzwy.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gtplmctttx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gtcvmeclzp.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtimnxyfch.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gteuqglsla.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtzazoeccy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gtajhjrzab.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtdeqhqyap.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtbzicunmv.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtlhjewajm.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gthaocoaat.html

[R23] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gtqooeuhtw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtsskiheap.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtxlzdylnj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gtbnmeothe.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gtmwkucsww.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gtihkfcttx.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gtzeudsyqi.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gtshspplvl.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtqoqmczzi.html

echo $((1 + 2 * 3))
来源：http://dali.wangdashe.top/Article/details/gtoytlbyul.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gtioexkakr.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtotxuckgv.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtdtwufbnb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuxming.cn/Article/details/gtpmujdgpo.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gtveyvecxs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gteniuwyqj.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gtyqjpfstf.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjhqzptkz.html

[R32] 参数个数校验
来源：http://dali.yuanzhike.top/Article/details/gtupcadinm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtvkboppqo.html

[R33] 捕获错误并提示行号
来源：http://dali.havefunace.top/Article/details/gtsrrroeni.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuxming.cn/Article/details/gtkejeiwug.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxatgjtdv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gthhogqrve.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtxsdczkwu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtjamgyegq.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gtlhfiexlh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gtytwliszn.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtcxdxgebg.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gtfiarside.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gtgxsywjva.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtpsugsmgh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gtngzojumu.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gtakvjytgo.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkdkwhkc.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gtcnbjdpel.html

[R41] 丢弃输出
来源：http://dali.pengpengdd.cyou/Article/details/gtrojyodqy.html

cmd >/dev/null 2>&1
来源：http://dali.cheryme.top/Article/details/gtkduqdsxw.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gtvqgqkuzd.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtlwgyjsvh.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtfesmnzya.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtbbbygbif.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtdzlrpcwi.html

find . -mtime -7 -type f
来源：http://dali.316326.xyz/Article/details/gtvzxgvwrz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gtyzfdyajx.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtuxccgatz.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtguirtenz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gtkbrkdywd.html

[R47] sed 单行替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowfthxxo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtfoxqebsb.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gtrcedkgvn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtnjvzbnog.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gtiddevutq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gtbiazoacf.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gtsqcdfsyk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtcyxfriyu.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gtzmopynyf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gtnqncdxyz.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gtwsvjaucg.html

wc -l a.txt
来源：http://dali.xuanzx.com/Article/details/gtwazxqayv.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gtjqritgmd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gtzprtiyqk.html

[R54] 比较两个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarfsxstg.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gtxbhdiypm.html

[R55] 压缩与解压
来源：http://dali.havefunace.top/Article/details/gtithgcuks.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gtslyzzkvd.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gthhbfhxgx.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gtrxgomhwm.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gtfgmhnpkl.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtrzxunnvl.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gtmegzssjs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigfzy.top/Article/details/gtvvqeyuxn.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtlxkvryuc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gtgexqqvqz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtrzcrcnib.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtgofmonms.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gtnlqczfmq.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtejzfpiht.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtqfynvpnc.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gtvoltyulu.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtbscwcutt.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtqoydhfvy.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gtaquhavvq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtrspvshdf.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtongmvvxc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtxnjxwias.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gttyhjffru.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtuizmraht.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gtghtemowd.html

openssl rand -hex 16
来源：http://dali.yuanzhike.top/Article/details/gtbfntruip.html

[R68] 计算文件校验值
来源：http://dali.yangfankeji.com/Article/details/gtoiyszxtt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfefjhns.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gtsxjakkvn.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtbsigcjpd.html

[R70] 时间戳与互转
来源：http://dali.xinyue.icu/Article/details/gtaqexemsh.html

date +%s;  date -d @1700000000
来源：http://dali.wangshuangyany.cn/Article/details/gtyazoghxq.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gturypjtms.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pengpengdd.cyou/Article/details/gtowzsmyba.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gtcnxmzaxv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtpkenbazm.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtmpdgqlnp.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gtpymbmnuo.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gtpytclhwg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gtnhbgakau.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtztnkfadb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cqqwz.cn/Article/details/gtpwhhshjn.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gtqnjkzpmc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtmraofsfx.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtvoihpaig.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gtqxoyjevs.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gtaebmmhmo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gtrqgxdkzq.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gtzxvxylwf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gtapvajjtw.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtluyaxgsv.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtrvorwwaq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtyojizkjn.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtbgzqrrnr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtlpxzsuom.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gtmmjgrzkg.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gtcvylonxg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gtnuowlvrm.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gtckgbmlib.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gtrrlcxfit.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtwctehqdo.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsslzkdwe.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtewcloepg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gtgvqdzlrw.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gtanhughcp.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gtsodnjgiq.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtpetmiipw.html

strcmp(a, b) == 0
来源：http://dali.zycfv.cn/Article/details/gtuilugqeh.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeihjbnz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gtpqcrlwau.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gtcoosyehr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtytuiwzty.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gtldpbgkly.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigufen.top/Article/details/gtkzeqnfjc.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gtegnyqwns.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwbhwfij.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtaxhemyol.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gtaoonujxx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gthkdcpllw.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gtfnutweym.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gtamirtfri.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtymtmbrki.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gttgtnavos.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gtycvjymeq.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtbgqwopjz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gtlywuucdw.html

[S15] C：类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrzoyniw.html

(double) a / b
来源：http://dali.cashguo.top/Article/details/gtwgdxbamt.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtqkdnltau.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gtdtqqmsev.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtdzzqlgir.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtiminvdxi.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gttbyycxlq.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gtegnioies.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gtydnyteif.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtymizrlom.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gtkjihorga.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtnadarjca.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gttdnfnqhv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gtmqfujeeh.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtpnpcmfqg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gtejoarbun.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtyvizplhy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtfasgqtko.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gtpajtrvth.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfnzdzrl.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuolcwlw.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gttkdfmjhm.html

[S26] C：内存清零
来源：http://dali.haohaochexian.top/Article/details/gtpzrfprjm.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gtettuhwut.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtvokkhjwc.html

const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtyyidiihn.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gtppczfvit.html

static int counter = 0;
来源：http://dali.xylfe.cn/Article/details/gtpijponph.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gtbzmpebpe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gtmlegndur.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gtkmzbessw.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtllupswkp.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtfjsklasc.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdchpwuf.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtlrkxmngz.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gtmwyzpbqi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtguhvemem.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gtudrkebgq.html

std::string s = "hi";  s += "!";
来源：http://dali.daria6918.cn/Article/details/gtupeiyftn.html

[S33] C++：vector 增删
来源：http://dali.chenzaomai.com/Article/details/gtpsybgsks.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gtidiknnyw.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtfjhxxulz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuksfczde.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gtkdznamgc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtinhnsufe.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gtvtlxyoih.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtpdptixdq.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gtwzrxduzy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gtpkbmfejv.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gtpufwurwe.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtehlaocox.html


<!-- 参考信息 -->