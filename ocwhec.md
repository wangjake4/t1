代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdqkwcmi.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2iyeqqdby.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2togeujti.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gt2ndwouthf.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gt2qdmejjue.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gt2rsaohazp.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztdmeqoo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gt2hcjbfdmk.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gt2ygpmlepp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gt2bcykbiyw.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gt2khbijfjz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gt2mmaksfeq.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwwfqkat.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2iwjfjswe.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2shltirrv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2marryxtj.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gt2btblgpzv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ysfwwfhi.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2vvkckvyc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2iwbskxff.html

[Q84] 去除首尾空格
来源：http://dali.yanxiufei.cn/Article/details/gt2cewjqtzm.html

SELECT TRIM(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2yfgdjjmq.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gt2ihkjljoo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gt2vtpmrisz.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gt2mbfehbjc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangdashe.top/Article/details/gt2hvhqfswx.html

[Q87] JSON 字段做条件
来源：http://dali.c1oappe.top/Article/details/gt2irnxpyzm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gt2oyszthdj.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gt2ipgohimq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gt2sphzgqob.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2cqceaaug.html

[Q89] 判断表是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yykjsttu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gt2zdpashzx.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gt2pwxsfcxa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gt2vfxgvtkr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2rvsstfgi.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gt2haxeyxis.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ckrbnhhe.html

[R01] shebang 与严格模式
来源：http://dali.xuanzx.com/Article/details/gt2tdqtrnsz.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gt2mqbafsrr.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gt2dtjxiwpz.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gt2fhrpgidi.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gt2uteixeih.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gt2bbcsycrt.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oatuwmbq.html

[R04] 位置参数
来源：http://dali.jinqigufen.top/Article/details/gt2hlopvids.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gt2gedcssnj.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gt2dkhtjnag.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gt2hmefckbb.html

[R06] 判断命令是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkeukgqk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2daepvkzi.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gt2hwilhyla.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2dfrdcath.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gt2tiiqaozu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxlsxrta.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gt2bfunnlpm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2etdqotjw.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gt2mijouhsh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjfpwhvi.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gt2iydnhklk.html

case "$1" in
来源：http://dali.xinyue.icu/Article/details/gt2yxvtpjlw.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gt2iqvtnddu.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gt2ifxiuupy.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gt2fxggyjot.html

esac
来源：http://dali.redwolf501.top/Article/details/gt2mptxcrfd.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gt2fbnvtsgi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gt2gjgkdsom.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gt2ycloengi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gt2fdqtldgg.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gt2bndtxuka.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvbehcje.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2lrzkqsff.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gt2mgndxtln.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gt2lzgluals.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2ighlpimv.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gt2dwkciqky.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gt2fsgzqoox.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gt2ltneuhsi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkqdvnmr.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gt2hspafulm.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gt2zpwisuxx.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gt2ezcafcpz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2byitnbmk.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gt2ngihtnig.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gt2fvibtbyz.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gt2vzyiejjl.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jtlrjyik.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2fdyyszur.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gt2stwsrosd.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbjxkzcs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yangfankeji.com/Article/details/gt2wrkmvmro.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gt2ijfylwaz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dashuyun.cn/Article/details/gt2esdzzuya.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gt2zxlzkhwe.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gt2bsmytcxo.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gt2qjzimtgf.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gt2jaarmqlo.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2tjulmhts.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gt2wqqjiesb.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gt2vdluvwjv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sufxvd.cn/Article/details/gt2vqwtncak.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gt2bbuvwwwx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258888.top/Article/details/gt2gdirhkxb.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gt2hplrlwob.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gt2sbgonuaa.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydrgkffn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gt2xmyilith.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gt2upawdnbm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gt2dxwtliyp.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gt2ghpndbin.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gt2hsssizrh.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gt2ibjwawgo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gt2kuitberm.html

[R36] 并发执行多个任务
来源：http://dali.yangfankeji.com/Article/details/gt2jmfeeooy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigufen.top/Article/details/gt2hledcdwd.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gt2ofkeswgq.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gt2xyjlkjzm.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gt2fyiakqbv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gt2txzfpwxj.html

[R39] 重定向标准输出与错误
来源：http://dali.yvedp.cn/Article/details/gt2smylgyam.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gt2xgzeyepz.html

[R40] 追加写日志
来源：http://dali.xziqi.cn/Article/details/gt2iyblgyqi.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gt2qwodnacy.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gt2gakcxvym.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2ekzqunjg.html

[R42] 输入重定向
来源：http://dali.jyoumei.cn/Article/details/gt2pffjdfss.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncfqclda.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gt2vrhcrihl.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gt2jvupfmva.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gt2wxcenveb.html

find . -mtime -7 -type f
来源：http://dali.fzhhl.top/Article/details/gt2lsloqwhc.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gt2mcrefmja.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gt2qwuacvii.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gt2vmkeglzw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gt2acawyoxe.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2fcymrpsa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gt2ndtocxht.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gt2uhzioumi.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2bsgpyknw.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gt2yqyvcyes.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gt2hfynuopc.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gt2qoeqlthv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2skxbvlnq.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gt2rccemorv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gt2gbvvupvo.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gt2pdmftqfd.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnyxgmul.html

[R53] 查看文件头与实时尾
来源：http://dali.quarkkingdee.top/Article/details/gt2vzxpbmyc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gt2ioywipnu.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gt2bqounexl.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gt2emhtwzkz.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gt2nujogncd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gt2pgerfwbg.html

[R56] 远程拷贝
来源：http://dali.xinyue.icu/Article/details/gt2ilvszduk.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gt2abwcbjme.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gt2xbeyxhpl.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gt2mjxbfzso.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2atzifukz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gt2cxzrnzmw.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gt2dunepzlj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gt2ocqgxmmc.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2fizqwslb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gt2ivouedpa.html

[R61] 磁盘占用
来源：http://dali.cucudq.cn/Article/details/gt2gahyowhs.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gt2jqvqknwj.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gt2fexdutji.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gt2bhjkmwdi.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gt2pyuuqses.html

free -h;  ps aux | grep nginx
来源：http://dali.kuanghao11.cn/Article/details/gt2zopdfoiz.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gt2xmdtayjq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaxclfy.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gt2wcgvggui.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gt2gtjlxwhu.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gt2wtigdlal.html

crontab -e;  crontab -l
来源：http://dali.sufxvd.cn/Article/details/gt2twdoynim.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gt2ghusphot.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gt2vzovhqkr.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gt2hoxcdvtc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gt2pcnvpmzf.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gt2mfhlkcea.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gt2pmlonhwb.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gt2sdmbcvsw.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gt2uhvvecuq.html

[R71] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gt2izbcneit.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sufxvd.cn/Article/details/gt2xzvtgbxm.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gt2upfvsftr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gt2medwylwo.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gt2rxplndrl.html

split -l 1000 big.log part_
来源：http://dali.cucudq.cn/Article/details/gt2tyibfbgf.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gt2zditabka.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shuidangran.top/Article/details/gt2hdhykihl.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gt2qpbxyert.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gt2nhajmyrq.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gt2ypwdeukq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gt2izmqlian.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gt2xwpnqtvr.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gt2ddfrejyl.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gt2jrkkdeuu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gt2spvtjbfa.html

[R79] 解析命令行选项
来源：http://dali.jiagoushi.top/Article/details/gt2npmmofoq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gt2cztwovlc.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gt2ysigmptt.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmlowcgt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2jiufcwho.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gt2fedpwtul.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmekqdsn.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gt2yxfemzav.html

#include <stdio.h>
来源：http://dali.hnxiangtu.top/Article/details/gt2muzjjlxb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rybocjdu.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2fhestcdt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zptrcbey.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gt2gtudplbq.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gt2mzgqthlc.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gt2uizbboey.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtwtmdmr.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gt2tahmisia.html

strlen(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2racamgyn.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gt2ttypkxpp.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gt2wfchjnnf.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gt2gcjrrbor.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gt2analiemt.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gt2euntgdnf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gt2dxesttsa.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gt2krydohpa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gt2jhkpqhyc.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gt2ipeakcls.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gt2gedxwuvd.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qsbrkaqh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gt2rooantju.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gt2sybdgtuj.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2kyauqsjv.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2vdmcrubp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gt2eyakghih.html

[S13] C：宏定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmaxfxup.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gt2lzrsahsi.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rssgladx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gt2nashdtuh.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2gyrkpomj.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gt2dkdraavn.html

[S16] C：位操作置位
来源：http://dali.sxryk.cn/Article/details/gt2ytjspxse.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gt2dvupjycg.html

[S17] C：安全拼接字符串
来源：http://dali.aizwys.cn/Article/details/gt2rutpdatx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gt2nvcmhngg.html

[S18] C：命令行参数
来源：http://dali.xinyue.icu/Article/details/gt2mhiigcct.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gt2iomiizud.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gt2zohmfzqk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2zgxvayoz.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gt2jkbthuqj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gt2ahfrxccz.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gt2zpcrlhej.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gt2zitwlxgn.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gt2awhrzvtl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gt2gyhvpkxo.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gt2diqtgdul.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gt2xgtsfsal.html

[S24] C：获取本地时间
来源：http://dali.xinyue.icu/Article/details/gt2fzdewmzj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gt2jalwpkwq.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gt2kokxfuoz.html

memcpy(dst, src, n);
来源：http://dali.hongshengwenyu.top/Article/details/gt2obtlxkxd.html

[S26] C：内存清零
来源：http://dali.aibaodan.cn/Article/details/gt2yorjwfol.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gt2jfasslae.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gt2tkmkpyez.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2knhgdsjn.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gt2btkustbe.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gt2wprjnhpg.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gt2tjapxcub.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gt2xludmzvb.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gt2efcorhhn.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gt2xgeiaggq.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gt2qtvfgycp.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gt2qwtuqmew.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gt2cjbpeqvw.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gt2mikrjywj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gt2aimxccfm.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gt2wygcbkbv.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gt2fcluohpk.html

[S33] C++：vector 增删
来源：http://dali.zhongyouzk.top/Article/details/gt2xackdmbn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fathktxr.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gt2jwgzuheg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gumktnxm.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agryuygg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2hvekxdka.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aaewlyyk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2xoilxoyi.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gt2jcjxcepb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.birdmap.top/Article/details/gt2hvfqvvje.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gt2yjglsgtb.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gt2qfwxccog.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gt2wnrxpnzn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gt2ctoueslv.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gt2grfbscdb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gt2zblpgpjd.html

[S41] C++：类与构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2emkeiqhd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2iaysrhwt.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gt2iqhegjss.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gt2ubtugrzk.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxmzjbzj.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuanzx.com/Article/details/gt2xkrceeip.html

[S44] C++：引用传参
来源：http://dali.shuidangran.top/Article/details/gt2ytuayalh.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gt2rzsxugjg.html


<!-- 参考信息 -->