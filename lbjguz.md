代发 wailian999

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtwaeitrvj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gtfwhbdeob.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gttvjwcafp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gtuxeyorkm.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gtptilekqg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gthnvmltps.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtzlucdvtb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.0kj1m.cn/Article/details/gtgorsamjk.html

[Q80] 字符串截取
来源：http://dali.zhiwuduotai.top/Article/details/gtnauoqmux.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtoixtlonc.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtnlfowjsc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtmmcfumqd.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gtojvphdei.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtfcofuzqo.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtzjwffbzk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtrcluvpbj.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gtwucyxmlr.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtcxprlhzj.html

[Q85] 数值取整
来源：http://dali.cqqwz.cn/Article/details/gtdjxjguvx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gtsbisibei.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gtcsrmfwqw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gtldhaekhd.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gttgthflqp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guannengcc.top/Article/details/gttwlsrfxx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gtqhmwkqrk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ybcxt.top/Article/details/gtdzhhpmny.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtvqjseuaf.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gtmibiibtz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gthoimjaox.html

[Q90] 生成序号列
来源：http://dali.tianlin.xyz/Article/details/gtoknunuoh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gtxbiudusp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtobslbaip.html

R. Bash 专题
来源：http://dali.9152youxi.cn/Article/details/gtajswblgp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkkpmlpch.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gtaeruajbs.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gttnnywbad.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gtdgqtbfec.html

[R02] 变量赋值与使用
来源：http://dali.zhengqikj.top/Article/details/gtocbjjpin.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gtujdznywc.html

[R03] 只读变量
来源：http://dali.ybcxt.top/Article/details/gtttejolhe.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtoscixkzn.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gtpyjkyvds.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sxryk.cn/Article/details/gtgaemtztq.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gteobkqpyv.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gtrcthywae.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvholqlsc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtljtvjvnj.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gtatfackom.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tian-w.cn/Article/details/gtxcdnmake.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gtpbhmuaqj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gthntarzoj.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtopkheiwc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gtkxxbjclk.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtxhjkbmab.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gtlpvcazmy.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdlpwdjg.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gtlkifafzh.html

start) echo "启动" ;;
来源：http://dali.yangfankeji.com/Article/details/gtwznymjew.html

stop)  echo "停止" ;;
来源：http://dali.guowangkeji.top/Article/details/gtiwrpuwdl.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtwxecmstz.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtnwymngjy.html

[R12] for 遍历文件
来源：http://dali.havefunace.top/Article/details/gtkypdmzzr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtporiyyxg.html

[R13] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gtxlnlmxrp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtjhdgqldb.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gturymekfe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gttnlpfkwe.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtudajbrqh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gtmxqfyaur.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtibphglpi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtahnzmgmo.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gtjktfmrea.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gtiuptigqe.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtnsrbsfgu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gtiwhkhulu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtswzchpeq.html

echo "${#arr[@]}"
来源：http://dali.guowangkeji.top/Article/details/gtgnbekkkv.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gtplbuings.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtiqyzimre.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtglkzutqx.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gtajczkzza.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gttrjqfrxi.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gtyawuelno.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gttxdvmlta.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gtthmoqdum.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtuhgdcxtb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzsvsjaq.html

[R25] 去后缀 / 去前缀
来源：http://dali.tanke756.top/Article/details/gtbomfeesd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.iojbl.cn/Article/details/gtbqblefoc.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtvyoelcfk.html

now=$(date +%F); echo "$now"
来源：http://dali.bjfxy.top/Article/details/gtuzdvobrr.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gtnmzbjiyy.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gtrmbxvlxx.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gtenpmsolw.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gtcmycgtxu.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtwdfxvnyn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtuxypsxea.html

[R30] 函数返回状态码
来源：http://dali.dashuyun.cn/Article/details/gtwdygpsyg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqaeczhp.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gtpnyjdufq.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbgrwweiz.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gtkolyborr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtvyzzuzdl.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gthqywigit.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yanxiufei.cn/Article/details/gtjmgspoqe.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtydlcyiql.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtrjuljcqi.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtyqqkhzic.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gttyvxujjc.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gtfpyygkuy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtxznhyrso.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gtwtlgimmq.html

files=$(ls -1)
来源：http://dali.jqgufenzy.top/Article/details/gtdepdlvvp.html

[R38] 管道串联
来源：http://dali.cashguo.top/Article/details/gtsfcbppox.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gtyijjmcvy.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gthxkqedth.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gtgnetgjko.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gtjhehcpjv.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsgyxvjd.html

[R41] 丢弃输出
来源：http://dali.nwbrower.top/Article/details/gtxvbcteaz.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gtlznmjzbk.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtqxbxoxde.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gtyiktcotx.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gtlqiguiir.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gtgdvbzwnl.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gterfarohz.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gtlzfveoog.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gtdoaoqpdl.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gtpivhvema.html

[R46] 递归替换文件内容
来源：http://dali.havefunace.top/Article/details/gtxolkwany.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gtetabkpka.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gtjvcglszd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtwamcgufl.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtmnbrsgny.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gthetpnslk.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtdngixexo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gtjdqrjhjv.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gtzdcmbewa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtlqykmeow.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsufxactm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gtxkdhfwxa.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gtmfkmrfmc.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtxovfwfwv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhoulong.xyz/Article/details/gtyxzxfrmf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtknlmllfm.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gtcajmbpqw.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtcvxrpxol.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gtigqrbpuk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gtridimbhb.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtqscsjqdk.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gtlgnqhqtt.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gthyhrlklq.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gtvdxtbyvw.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtyjsguspi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gtchzpkodh.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtljaoqqdu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gtweyltbkp.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtmmarhhca.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gtejrouvcc.html

[R61] 磁盘占用
来源：http://dali.xylfe.cn/Article/details/gtfbpujgqe.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gtyqqfgdjp.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gtgxsmsorm.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gtkekdnsoj.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gtooftkryo.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtgbfbhbht.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gtnjksrrkc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gtzlgbgewk.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtyfcfntzo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgufenzy.top/Article/details/gtaeqdemov.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gtbhtthbeq.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gtiuidmsny.html

[R67] 生成随机十六进制串
来源：http://dali.kuanghao11.cn/Article/details/gtifwxipat.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gttfosyoha.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gtzvmowbxd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gtenlwnzzs.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gtvgyeobtl.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnqzz.top/Article/details/gtqormbtib.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gtoennfjns.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gtrpsplgmh.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtaikiwmoy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtsdrdolqc.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gtjgpuloyv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gtcztxwmnl.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gtqkiwemga.html

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gthpkmazkt.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gtoeghwocu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gtiyvonwof.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gtgmvjhink.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.9152youxi.cn/Article/details/gtupyjtoli.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gtduirdryb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtqtcfysyi.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfjsphss.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gtrnxackrt.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gtmwyfekds.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtqhxqdbhv.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gtafadgqrd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gtxxhtqdjp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjclozgwu.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbjgppsq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtyetsrgbs.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gtwjoirbep.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfvuycosv.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gtlwmkplxh.html

#include <stdio.h>
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwuzqjow.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gtjdecyvmk.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gtqhdqhekn.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gtocuofzrg.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gtyhmaaltq.html

int x; scanf("%d", &x);
来源：http://dali.yongpay.top/Article/details/gtrcunemdx.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gtvkwpcbaq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gttrlipxkm.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetaovfmp.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gtgppbbrkh.html

[S06] C：字符串比较
来源：http://dali.havefunace.top/Article/details/gtxtlquiei.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gtyawsepai.html

[S07] C：数组遍历求和
来源：http://dali.ydzc1.top/Article/details/gtnhfaxwnd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gtwguooicz.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gtnoapomvt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gtpwsmexoo.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gtpmxtcpfb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gtfkxyvctk.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gtxrpyesxf.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gtdftyirur.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtgdpbfgvq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gtjexzmbyv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gtxtkifhtr.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtujyahshw.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gtkyhbbeji.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtvocyvmtb.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gtmblqaces.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fengsongda.top/Article/details/gtdlrwizaf.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gtfugzybpm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gtkikygeah.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gtujmlljbf.html

(double) a / b
来源：http://dali.wangdashe.top/Article/details/gtkbdulbzy.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gtahqqvjei.html

x |= (1 << 3);
来源：http://dali.vqdsnc.cn/Article/details/gtkbfuxvzu.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtpbuxwvpc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gtzzkwhqtr.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gtzhcztfsl.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gtyhxikmun.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gtdrgotjcg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtkfyrgcbs.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtayhzlpyg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtnomamjag.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtytofpxkk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtnenzbdst.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gtkbdyyqcp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gtufnkalhi.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gtkpvdrwgu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sysykeji.top/Article/details/gttiighgoi.html

[S24] C：获取本地时间
来源：http://dali.chenjidiqi.icu/Article/details/gtkrbmloft.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gtgpjpmydr.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkiioyyc.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gtxpprmwpf.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gtlgdrpbxm.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gtiegwwmdf.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gtjwrrltmi.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtimfkbapq.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gtkpdkpcdx.html

static int counter = 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmrakzxi.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gtcfwgujjd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gtdtrirmto.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtktcuhuly.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gtqvzjdndl.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtnkvfyqug.html

#endif
来源：http://dali.feifeiyinyue.top/Article/details/gtahizvmub.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gtlodgwxnt.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtazldijat.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuanzhike.top/Article/details/gtyeqcucjq.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtnijqawcl.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gtalqjsxjx.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gtqthovcij.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gtcxlkrkhn.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbenvmer.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gtvcwufubr.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtryuehdoc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtcykxiddy.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtgfhxokyz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtktoyafgx.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gtwnagyeow.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtmzlgccek.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gthjlzfgcg.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtrsbvktnl.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gtawwdryhg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gtdnejfabk.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfymfxvtx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gtqhzaotex.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gthidcmxlj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gtjvfgpqov.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gtvbsafkbf.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxinkj.top/Article/details/gtmriceqpd.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gtmjomwmcs.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gtsubkogih.html

[S44] C++：引用传参
来源：http://dali.tanke756.top/Article/details/gtciqriclv.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gtygafznjw.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gthfvmapuq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtptrjrbkr.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtbwpwpgsg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gtidbwcuyk.html


<!-- 参考信息 -->