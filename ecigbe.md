代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gt2scalriye.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kvtzvxcp.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gt2xbpdqgde.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigufen.top/Article/details/gt2yulhzpep.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2lpqrzhch.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gt2fsjfqksr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ufynjhme.html

[Q57] 行号
来源：http://dali.jqgufenzy.top/Article/details/gt2yqsevpos.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2yxnfgpxq.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gt2psnsdufc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2jnrrmwau.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gt2spsdgysd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2moojjqlc.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gt2elujejwi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gt2whpgnyqe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2wgvoxedb.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gt2iqnajsmb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plmccxwh.html

[Q62] 分组占比
来源：http://dali.daria6918.cn/Article/details/gt2zubnhqky.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gt2nxonzlyc.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gt2xdyudrmz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gt2izkrcteg.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gt2edbelink.html

COMMIT;
来源：http://dali.birdmap.top/Article/details/gt2yamapapt.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gt2yxtdppzt.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gt2lvufdfjx.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gt2vaqunrrr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gt2yctsjhmq.html

[Q67] 设置隔离级别
来源：http://dali.chenjidiqi.icu/Article/details/gt2unuleyui.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuanzhike.top/Article/details/gt2mkjxiiry.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gt2fkvuwoia.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gt2blcrvaon.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gt2mqqokaad.html

[Q69] 查看执行计划
来源：http://dali.hammf.cn/Article/details/gt2qlnxplxy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gt2nbtrmzss.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gt2bszdbjqq.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gt2xzflgtbv.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gt2zkcfxzuz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gt2vncrmrbh.html

[Q72] 查看索引
来源：http://dali.hnqzz.top/Article/details/gt2mmrbrlxs.html

SHOW INDEX FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2gwwzloka.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gt2khtqbinf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gt2gjaepoyv.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gt2dsxfbchm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gt2htqjtckw.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gt2mywjffxw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2gbqzmonp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jianghu66.top/Article/details/gt2itnnwedt.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gt2tmocczbe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gt2soarbuql.html

[Q77] 时间加减
来源：http://dali.tianlin.xyz/Article/details/gt2kckwiexw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gt2pbczunuf.html

[Q78] 当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2mwcqbgkh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gt2bodmcivp.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2enhpmkrz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gt2bqxhkqhu.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gt2xdvwnwzb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2tslotrmy.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gt2rgjroiag.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2tfgvyohc.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gt2ixyshxmt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqlsbryc.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2zjfwbvup.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2mxraopkg.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gt2zloocuha.html

SELECT TRIM(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2zszuuqxm.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gt2hsjdrfzf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gt2tzzrlyzw.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gt2bskrxumy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gt2jovlwhht.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gt2tkianjkt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gt2dmxnfvuh.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gt2rglvmsuz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gogol.net.cn/Article/details/gt2guobcxqc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2hemcxaxf.html

[Q89] 判断表是否存在
来源：http://dali.hammf.cn/Article/details/gt2ghgwgtet.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gt2vztrzguo.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gt2ujvncugl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lswsxpkx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2hlsdozkp.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gt2qifgxobq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2monntfrr.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gt2exhenokb.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gt2ltsxghai.html

set -euo pipefail
来源：http://dali.daxiang520.top/Article/details/gt2czzpkwqb.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gt2qhfgklut.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gt2ctoeuaax.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gt2iwkmgkgl.html

readonly PI=3.14
来源：http://dali.dashuyun.cn/Article/details/gt2qspclfky.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gt2rzkazfgz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gt2gjxukumm.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gt2qchzumas.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imjkonsf.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gt2wnexvdtt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gt2kfdtwwsh.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gt2ofolfuji.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gt2igogctpm.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gt2xvcygkgm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xinyue.icu/Article/details/gt2krzlzfoi.html

[R09] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2etlvisek.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gt2xlqtclzx.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gt2jpxkxfiw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.meibo888.top/Article/details/gt2csrmbjbn.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gt2hxomhjck.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gt2dvzeavpl.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gt2fkuolkwz.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2ipggxxnh.html

*)     echo "未知命令" ;;
来源：http://dali.havefunace.top/Article/details/gt2jcfdzoil.html

esac
来源：http://dali.c1oappe.top/Article/details/gt2yzdfgdou.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gt2lulgwltf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gt2fpwmmcej.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gt2bmlrrtoh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2iltyzqpw.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykbcosnd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gt2zgpaimbg.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2tpicqgye.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.snrcjt.cn/Article/details/gt2jfimiagw.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gt2uqfxjtrj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gt2pidunvfm.html

[R17] 数组定义与取值
来源：http://dali.birdmap.top/Article/details/gt2fyvpfytd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gt2imimqfbe.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2abkrostg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gt2vewxgpsa.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2wrvtpqfd.html

echo "${#arr[@]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdetaezb.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gt2kaboyybk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.redwolf501.top/Article/details/gt2mubykljk.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2vfgjflmu.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gt2wfgpnqwf.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gt2lsahbkik.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gt2pgayafkv.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2hrykaljr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfhickeu.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gt2skhnmkip.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gt2mginteic.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gt2yrdoeqcf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gt2hjjqwmtf.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gt2isnhsjkg.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gt2gdvvaukl.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gt2bezsxqhn.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uggkfhmf.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gt2hocuslbn.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gt2owhqsezn.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gt2xohixxny.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhongyouzk.top/Article/details/gt2pdwohdlq.html

[R30] 函数返回状态码
来源：http://dali.havefunace.top/Article/details/gt2whtnfrqs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.mhx1999.top/Article/details/gt2puojcusb.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gt2dkyuwbwt.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gt2qsbnuacg.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gt2ulxqpvdp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2abbsuvrh.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gt2ybzpgfnz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gt2imtbydde.html

[R34] 退出时清理
来源：http://dali.yj20258.top/Article/details/gt2fopfmjhn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khqfepmo.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gt2biuphmmp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gt2aenaiewi.html

[R36] 并发执行多个任务
来源：http://dali.havefunace.top/Article/details/gt2fithgpqy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gt2xxnimhip.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gt2bogoufia.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gt2knynqcmq.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbeyzbsv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oixxwkhz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gt2qeczdoxo.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2nwxyelkc.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2gyjgbpdf.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gt2notnwerq.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2janzlybs.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2iecrzjeu.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbkfifqz.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxxgthsk.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzkhefjc.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gt2lsjbsbmz.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gt2mnlbxoky.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbtsytll.html

[R45] 批量删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2scphdsoz.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gt2spwafowp.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gt2rjtiaccx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gt2oqfabrxy.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gt2tfchvlcf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2jyvtoxlj.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gt2ltuesgss.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2dydddtwr.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gt2cuxyctir.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifdujhri.html

[R50] awk 求和
来源：http://dali.xuanzx.com/Article/details/gt2ogzwflha.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2ngziqitf.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gt2hylckrbu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gt2bkwirogg.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gt2zlumhnkh.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2jvscojra.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gt2kdlcdhxp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gt2ysnyitlv.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gt2bfugqkmm.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyhjzgye.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gt2idloynpv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gt2mobcdrtg.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gt2kwnbqwha.html

scp file user@host:/path/
来源：http://dali.pengpengdd.cyou/Article/details/gt2leocuysa.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gt2ijfhojza.html

ssh user@host 'uptime'
来源：http://dali.jyoumei.cn/Article/details/gt2liclnmmt.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gt2tueywlsi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gt2rgvbhbht.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bavcxith.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gt2cdljtyzd.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gt2zbygvoeg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgklcdgw.html

[R61] 磁盘占用
来源：http://dali.shangyingyoupin.top/Article/details/gt2lyhbcgei.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gt2ghhrfbfi.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gt2nfzzwscc.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmtqdrhx.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gt2xittexiu.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwfqtpbq.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gt2kaxftmoq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gt2abbpuycr.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gt2nrapxivc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gt2rofifjwb.html

[R66] 定时任务
来源：http://dali.hammf.cn/Article/details/gt2vxhuljzm.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gt2wznlmxuz.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gt2qgaqaryk.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gt2kkrxyqbd.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gt2hhtgvurn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnqzz.top/Article/details/gt2juclpwbn.html

[R69] 生成随机密码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otkaeacx.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gt2jmzvnwfu.html

[R70] 时间戳与互转
来源：http://dali.yueranfly.top/Article/details/gt2vnqvhlzf.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gt2edyhjvgu.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gt2djzpsavt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gt2zqpwfjef.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gt2tgvrkjqk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gt2uhofkhvf.html

[R73] 分割大日志
来源：http://dali.yj20258888.top/Article/details/gt2eofwwepg.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gt2zefppocu.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gt2ymxsslgn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uatjtxis.html

[R75] 导出环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2gywvnmzc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gt2pvbexmnl.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gt2vbxjsckq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gt2sgooygfc.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gt2ropvclay.html

read -rp "请输入: " ans
来源：http://dali.nwbrower.top/Article/details/gt2tztligix.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gt2fmoyiraw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gt2pgaqhgfx.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gt2kukskkwg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzawunro.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gt2hzutamik.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gt2iqjawmbu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2wqygcoek.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gt2vphsakdh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2vbsuaxvk.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2tezcnxjy.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gt2bbcbykir.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gt2saovpbdh.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2zuicywye.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gt2sjegsobw.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gt2imynjlgf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxulynzd.html

[S04] C：字符串复制
来源：http://dali.sweek.top/Article/details/gt2afplbeyc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2vzxooyff.html

[S05] C：字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2llrftbjk.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwmgxepr.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gt2coukkyik.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gt2pmvetjdp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2adtnybvy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gt2uqblpakh.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gt2itqkqdzp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gt2ceekpgnd.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gt2edttzpef.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yongpay.top/Article/details/gt2poubsvra.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxeoppoa.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gt2tkssgvyb.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2jeywywso.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guannengcc.top/Article/details/gt2poylgkxw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtnbabcz.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gt2kgefhvzp.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gt2xjflwdre.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2bvgoohjk.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gt2snrthjew.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gt2nmevpbgl.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cuqjnuua.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daxiang520.top/Article/details/gt2qilgsvnh.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gt2mykgbzyi.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2raczbkqv.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gt2kkptmlgd.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gt2tgnkctcy.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2wbbifser.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gt2clsqbqzr.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gt2ohutbqvt.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gt2xjijcpxa.html

[S19] C：快速排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctpdnfpp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gt2wbmdwcrh.html

[S20] C：二分查找
来源：http://dali.zycfv.cn/Article/details/gt2gmugszpt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2fyjvbmtf.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gt2atbfewcl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gt2jhrhimed.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gt2fdmgvbes.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gt2emuigupa.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gt2bkgjveld.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gt2zhqkmsyg.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gt2fusgslek.html


<!-- 参考信息 -->