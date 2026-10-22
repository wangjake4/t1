代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yongpay.top/Article/details/gt2ywvlwxsk.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gt2ujyyiadh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2zwldsiyz.html

[Q53] 按条件删除
来源：http://dali.gotoacloud.top/Article/details/gt2dtjzufqo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfgbyiel.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gt2penhkndu.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gt2hqvifsym.html

[Q55] 排名（并列占位）
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtbgmoef.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkapjgvf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzflsnhi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gt2iaipeduw.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpmdknru.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2wmhtufdw.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkkoqbps.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2izqvsgvg.html

[Q59] 分组内累计
来源：http://dali.bjfxy.top/Article/details/gt2prtoddmj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2nljvntrm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zdqjudy.top/Article/details/gt2nyvwwmnb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gt2rctfqyrg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2hlkcmbjs.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gt2wcwmrpsu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2unuddbsa.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gt2qoljlbfm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2biftzjyt.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gt2yshmbfib.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gt2jihffnrx.html

[Q64] 提交事务
来源：http://dali.hammf.cn/Article/details/gt2jglwzmzo.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gt2exknyhqc.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gt2dytydmnd.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gt2bknohdsc.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2maozhzwh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gt2hvqozrtc.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gt2vovdrbac.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gt2mbcxcmrs.html

[Q68] 保存点
来源：http://dali.gotoacloud.top/Article/details/gt2lztnbzxp.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gt2yynokebd.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gt2bemoanxp.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gt2hevpmvfz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gt2qjryqzmz.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gt2sliullku.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gt2aerbywsh.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gt2rzpkcald.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gt2azkaxjae.html

[Q72] 查看索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2irnqfeun.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2fhvmburi.html

[Q73] 查看表状态
来源：http://dali.gzhubu.top/Article/details/gt2mwgsbrqj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gt2vnvjaoub.html

[Q74] 强制使用索引
来源：http://dali.pycfn.com/Article/details/gt2gfpbokhc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258.top/Article/details/gt2lwpukesd.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gt2qairogbv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2ghegvsgm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gt2auwgsnuh.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awyytybo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gt2pgcvfibg.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gt2auoiysnf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shuidangran.top/Article/details/gt2cbukqsbf.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gt2qiwypdtp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gt2rhrskepl.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2ipiewhcn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gt2jtlcrbzo.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gt2wqimfcgl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2lqrshbws.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gt2bkpipgxg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahndnmtq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qubuljkd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2vbuvngvh.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gt2gkeruqyk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnvsoepw.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrsgtiif.html

SELECT TRIM(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2rtfwnsyk.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gt2shmrwzxw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gt2dcrrpjkg.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gt2tlidgkbn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sysykeji.top/Article/details/gt2dtiwdohe.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gt2ekbtknfh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zscjlmzh.html

[Q88] 行转列（条件聚合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvydeejf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gt2pjdkkngz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2nldtljrc.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gt2eeenjrwa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gt2nozrwyum.html

[Q90] 生成序号列
来源：http://dali.fengsongda.top/Article/details/gt2azzhovth.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gt2sdavnzdi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqlkvizw.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gt2jkwcaegj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2xvxjnqjy.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gt2pamtprod.html

#!/usr/bin/env bash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmmzzjct.html

set -euo pipefail
来源：http://dali.zdqjudy.top/Article/details/gt2iwyeprgv.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gt2kgwcvnms.html

name="Tom"; echo "$name"
来源：http://dali.vqdsnc.cn/Article/details/gt2obeiodfl.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gt2bxngjrkv.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gt2cnaevpix.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gt2eiusmgpi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gt2alrwhdbi.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2jjyaaqkl.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gt2ebacjude.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gt2zyzezktb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2wwlekafs.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gt2khobissv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbsqhyhj.html

[R08] 数值比较
来源：http://dali.vqdsnc.cn/Article/details/gt2sftroerx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gt2fxdgtjpt.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggdoydpb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gt2aleuacyh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tovzwida.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2poeckjnt.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gt2bvluxbgg.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knhrudwh.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2btfcmumr.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gt2ygfijpnx.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gt2pilwgjyv.html

esac
来源：http://dali.xziqi.cn/Article/details/gt2fihmbhwq.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gt2ojrzalqt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gt2kalwpvim.html

[R13] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gt2qsozuofv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywuqvmwx.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkwmiqby.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfoparuz.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2mfpqkssj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gt2wdwfowgq.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gt2bquctwfg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gt2zlrrnexg.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gt2xzgjwvpa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gt2akogbuue.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqavnbsu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gt2atiaqrya.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gt2ujopxylw.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gt2kwkuovqd.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gt2zlsocajd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2zimiycxy.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2gblsgwkc.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gt2hplmjpuj.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2fmbvndgx.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gt2kyhnmcjr.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gt2equplihf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gt2ybplfoez.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gt2axpookml.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gt2iloarcvu.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gt2kownoote.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2tchuzfen.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ooksvzdd.html

now=$(date +%F); echo "$now"
来源：http://dali.yangfankeji.com/Article/details/gt2ddyeaszx.html

[R27] 算术展开
来源：http://dali.sysykeji.top/Article/details/gt2cwjsejwb.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gt2nyuuydnr.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gt2biftbsuy.html

echo "scale=2; 10/3" | bc
来源：http://dali.shzxlz.cn/Article/details/gt2wfqpdmrx.html

[R29] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gt2autxgwfx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gt2lbndhjzt.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gt2akxtaskp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gt2iidcukcj.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gt2xxtzefge.html

f() { local x=1; echo "$x"; }
来源：http://dali.gogol.net.cn/Article/details/gt2xwcnbubq.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gt2jobnijzc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrtknhbu.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gt2rbqanrxk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gt2lcqicxuo.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xozqwywg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2ydawzerq.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gt2soilqluk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gt2scwxnmqp.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyfeiqfr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gt2tfsobwoi.html

[R37] 把输出赋给变量
来源：http://dali.cashguo.top/Article/details/gt2bwvwelou.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gt2gmedyhiy.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gt2xllcyugv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gt2rptgjxkm.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gt2frtvvscd.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gt2kbikrahg.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gt2eqsorgnk.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gt2pgrzvuql.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gt2ebgefxjc.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gt2mwcpbdku.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gt2tyxjdhgl.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2gkumkijm.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egvqxvnu.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gt2qgtzxljg.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gt2hkfgpwsu.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gt2aomacugw.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gt2rmscgnac.html

find . -name "*.tmp" -delete
来源：http://dali.xuanzx.com/Article/details/gt2zrnbevjv.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gt2eensjvao.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gt2iehhvdmp.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gt2vmxotaea.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2xkssyxen.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gt2coutjybk.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2eimslwii.html

[R49] awk 带条件
来源：http://dali.fengsongda.top/Article/details/gt2bthlpbwk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbjvxwnd.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gt2mcdknrxf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdgihruy.html

[R51] 排序去重取前几
来源：http://dali.c1oappe.top/Article/details/gt2fxnnntfi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gt2gxoshuby.html

[R52] 统计行数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocoasnkt.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gt2ehpdhtap.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gt2dxlqodss.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gt2dheppiox.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gt2llkkcgsu.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gt2lvjeqwcp.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gt2ojninocb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gt2jeqgcrlx.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2qpnponqi.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gt2kinaxjzy.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gt2ddghoelm.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gt2bciugfys.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gt2ltemntdc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gt2pskvmpln.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqbggeqi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.redwolf501.top/Article/details/gt2ukvcxmkz.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gt2aagwdhqv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuanzx.com/Article/details/gt2owxmdemm.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gt2mcwtvbok.html

df -h;  du -sh *
来源：http://dali.c1oappe.top/Article/details/gt2bvnrpnoe.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gt2dxxduspu.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gt2vplwywrz.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gt2xernapie.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gt2ibivzbdw.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gt2hxnqymxd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gt2oyjcqrdl.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gt2eoayiusc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gt2fjyezrnn.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gt2fzgnvslj.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gt2mnvaiafk.html

[R67] 生成随机十六进制串
来源：http://dali.chenzaomai.com/Article/details/gt2cgtmdnra.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gt2mnqkssqn.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gt2canvydrq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gt2qxzbjuuw.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gt2yhxabukc.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gt2puazchsi.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gt2nxkjvjrl.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gt2beyliddx.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gt2jhrulbev.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gt2ukrfvxgr.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gt2rhrcjzdl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gt2jcjhbawr.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gt2yaeklrst.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gt2upiagdyr.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gt2ijrofclk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gt2zbviqqxe.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gt2bjjjjajw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gt2znlmshlj.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gt2igyglnow.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gt2eyajlcee.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gt2wdhucimq.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gt2qusjpefv.html

[R78] 交互式菜单
来源：http://dali.nwbrower.top/Article/details/gt2yqjsxfhp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oljgvtlc.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gt2hfwkhfxa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gt2bypsnfsv.html

[R80] 查看脚本执行耗时
来源：http://dali.dashuyun.cn/Article/details/gt2zwhqdivs.html

time ./run.sh
来源：http://dali.xinyue.icu/Article/details/gt2mmnpyoxc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2gwthhtfw.html

S. C / C++ 专题
来源：http://dali.shuidangran.top/Article/details/gt2ogibzuxz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2lhbjahcc.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2vclgplip.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gt2ojprcfjl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gt2rggnncni.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gt2yvekmbnh.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gt2obqbomfk.html

[S03] C：读入整数
来源：http://dali.iojbl.cn/Article/details/gt2clwakrwx.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gt2warqxuzq.html

[S04] C：字符串复制
来源：http://dali.ehwqpu.com/Article/details/gt2wvtbhuqk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2najpzmdu.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gt2xcuiatrf.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gt2zmlnyxnf.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gt2jlivmolb.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gt2mbsukjlu.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gt2suaibare.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gt2tlqidehi.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gt2cpgrayuo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gt2tmbjqzhu.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gt2dgxzpbhr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nwbrower.top/Article/details/gt2aindavyg.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvwjgfdv.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gt2ptxqhuwd.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2exfeootg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnqzz.top/Article/details/gt2ngsdotgx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.mhx1999.top/Article/details/gt2ydebbuxb.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2eoqhbxyg.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gt2tyoloyak.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2yxqecfkn.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gt2fucicvuh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gt2mbpddddr.html

[S14] C：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocbttmxc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrtcoskx.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gt2wccggluq.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gt2hlilzwbf.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gt2hpymckzk.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gt2offiacyt.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzeememk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gt2evhfltyf.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2ytmyunad.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gt2nnoooqxe.html

[S19] C：快速排序
来源：http://dali.cdnleiting.top/Article/details/gt2sxmfsbib.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2vmhhshda.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gt2nkmqzvwv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gt2kwnynrep.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gt2kwfjwfmx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258.top/Article/details/gt2kajtvrdc.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gt2raxxodoh.html


<!-- 参考信息 -->