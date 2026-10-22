代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2tpdwmwnk.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gt2svuimyrm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2ulrnygyo.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrdfvoax.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2cjjebavr.html

[Q52] 删除指定行
来源：http://dali.zdqjudy.top/Article/details/gt2kvkvkzcs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2bbvqdwtt.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gt2apekjfbb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gt2rbozaayp.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gt2jyyledet.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gt2tfypfkfy.html

[Q55] 排名（并列占位）
来源：http://dali.pycfn.com/Article/details/gt2zruzvhpr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gt2javxnwgi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gt2qmrxkgfi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gt2rqzsbagk.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gt2fwppxsrh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2lxmqttpl.html

[Q58] 累计求和
来源：http://dali.jinqigfzy.top/Article/details/gt2okfvrwjy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2qahcamjg.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gt2zdayignf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2zwowylcx.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gt2rfxxmbei.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gt2rfxuzolp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2rdlanizb.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gt2uxshodta.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2nyzwuqmj.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gt2xlqnuydm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gt2lulndlxx.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gt2ogoyymcd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gt2lsklfplp.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gt2qhnpnnfw.html

COMMIT;
来源：http://dali.jlsjyb.cn/Article/details/gt2sspzvsaz.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gt2ytbdfwrq.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gt2nrpltipq.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gt2ubxaldim.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyelmstm.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gt2znskixku.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangdashe.top/Article/details/gt2eukpmdpm.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gt2hwivqcyz.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gt2wpqmtlzq.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gt2sokayqih.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gt2blsqilby.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gt2zzkrwlkl.html

[Q70] 更新统计信息
来源：http://dali.zycfv.cn/Article/details/gt2modtmqxu.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gt2kncqejfd.html

[Q71] 查看建表语句
来源：http://dali.zycfv.cn/Article/details/gt2mqnvioya.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gt2qtdhzkvy.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gt2vzwyjxsd.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2fgamorcg.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhjjhuih.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gt2efjojefy.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gt2rjzikdox.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ybcxt.top/Article/details/gt2xxjquulg.html

[Q75] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2zrmaulim.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2njwarjew.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gt2kskxqpan.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gt2bgfxdnyx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gt2cyjrahqr.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gt2sxbxeazm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gt2ovgbdewz.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2obtjpydu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gt2hssqyolm.html

[Q79] 字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gt2tskasxzp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gt2ugloclba.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gt2ittlrujd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2xbfogpww.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gt2gxlmlpwr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gajfvfyf.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gt2fhcpnosz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2upoqteuv.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2mfoslaig.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vovquepc.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gt2khycuyak.html

SELECT TRIM(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2wrvqvbzr.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gt2wbfpwsiz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gt2lfcrcphq.html

[Q86] 读取 JSON 字段
来源：http://dali.tanke756.top/Article/details/gt2euejhnxi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgtlszri.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gt2ukshjyvh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gt2uhopeoyz.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gt2lccxtoon.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfuitkdt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2dqhsrpyo.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gt2ftejbqau.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gt2sfuxhkil.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gt2iikimdbc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gt2vjaveaah.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2diakkybm.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gt2ulbccgrn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2invtuqle.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gt2pwxncwjj.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gt2ufcdpxry.html

set -euo pipefail
来源：http://dali.jqgfzy.top/Article/details/gt2hxsmtslt.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gt2mhsjqbad.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gt2frfkbkrp.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gt2cxplkowj.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gt2rmbsetyz.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gt2jrbzglai.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gt2qhzgcpsd.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gt2gqytlzuf.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gt2evomizmq.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gt2glasqkcq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gt2pehzjgmc.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gt2hxgcujjk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2dcfuipkr.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gt2jhikyyhg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2foqrhnix.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2iljpsmps.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2tdavmplg.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ihrtpvhm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2ywrrmsol.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gt2ywuulbby.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gt2xsqtdpex.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcrhsyhh.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2rlwokeld.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfyiitzw.html

esac
来源：http://dali.shuidangran.top/Article/details/gt2eqtddeis.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gt2llcrkdkr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gt2vdmttcun.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gt2hfveimjq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gt2cycjabdf.html

[R14] C 风格 for
来源：http://dali.fzhhl.top/Article/details/gt2yeihpoga.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2dxwdeplm.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2qmpxamso.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yonumen.top/Article/details/gt2prqhsgrn.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gt2hgabztpt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gt2uiguvkmk.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gt2prnmiths.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gt2uhzbgxfx.html

[R18] 遍历数组
来源：http://dali.c1oappe.top/Article/details/gt2ronttqan.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2vznhvjht.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jfpquclg.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gt2rrcvehcp.html

[R20] 关联数组（字典）
来源：http://dali.cdnleiting.top/Article/details/gt2mysimfpl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gt2osglsnxi.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gt2uljtxqwg.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gt2wsyyhmhp.html

[R22] 截取子串
来源：http://dali.aizwys.cn/Article/details/gt2arztmycd.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rsawqvdf.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2ipwgrlzg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fengsongda.top/Article/details/gt2uwmcjygh.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2duhokpjt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gt2ixytgdik.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gt2kzqunxbc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2saopiira.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gt2raamjern.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gt2jzmykbyy.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbmhlycw.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gt2zgynjthm.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gt2oyqkmqlq.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gt2kluozxko.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gt2xvsspeon.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gt2fikulgcz.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2bsugutvk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gt2zsnylcwb.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gt2qebavblv.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gt2pdnpgtgq.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gt2fgbtuhyq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2worjenbw.html

[R33] 捕获错误并提示行号
来源：http://dali.yvedp.cn/Article/details/gt2ueaqyiqt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gt2scopxdsa.html

[R34] 退出时清理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uyghvuwu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gt2bhctfzaf.html

[R35] 后台执行并等待
来源：http://dali.zhengqikj.top/Article/details/gt2ejjaewzm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gt2uryhglaz.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gt2ceqfuefd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gt2gmqtdfgm.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gt2fqidiair.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnubulwq.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gt2ntmazeie.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yueranfly.top/Article/details/gt2hxbxhvvk.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gt2wbxvsszv.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2vgimrmgh.html

[R40] 追加写日志
来源：http://dali.snrcjt.cn/Article/details/gt2rzxdhxpk.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gt2aecidxha.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yonsrcce.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258888.top/Article/details/gt2txggfmkf.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gt2jugyhqfs.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gt2apxzxpqh.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gt2iuwoqpvs.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gt2tijgogdj.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gt2mxyuvkab.html

find . -mtime -7 -type f
来源：http://dali.aizwys.cn/Article/details/gt2xrmzrbto.html

[R45] 批量删除
来源：http://dali.jianghu66.top/Article/details/gt2crretxvc.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gt2creoguch.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggmuwltb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gt2mzipzrki.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gt2asjzfybt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2dxvhkywc.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gt2qeeritpl.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2uiaqccts.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gt2usxtjwiy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gt2hmjahanq.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2zuibdhfa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecwhecrc.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gt2mhhbxjwi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gt2mrmmwbsp.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gt2spmqwqng.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2hbezhvgw.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gt2znhhhsah.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gt2norjflao.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gt2ytauchng.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gt2tgqawpjs.html

[R55] 压缩与解压
来源：http://dali.gaohongyu789.top/Article/details/gt2yjchummk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.kuanghao11.cn/Article/details/gt2sbkjiqsc.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2ufabgjep.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gt2wkhpxfmc.html

[R57] 远程执行命令
来源：http://dali.yuxming.cn/Article/details/gt2gigffkbq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcqafer.html

[R58] 下载文件
来源：http://dali.sweek.top/Article/details/gt2ndbqgzhq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gt2qkykdssl.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghdkuonw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gt2kcgnlcvv.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gt2fpyggtru.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gt2ahkxnjtz.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gt2pjtjosoh.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gt2wonmttdx.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gt2ogrrabdl.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gt2xilyfjsw.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gt2dyaukdhm.html

free -h;  ps aux | grep nginx
来源：http://dali.ehwqpu.com/Article/details/gt2ggzesvpj.html

[R64] 结束进程
来源：http://dali.zhengqikj.top/Article/details/gt2sfsgcxsj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gt2npacnoam.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcgcjmkv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gt2oukayleb.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gt2pwqvgmar.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gt2yxxcadxe.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzhonrml.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztvprrhj.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmxadcko.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tian-w.cn/Article/details/gt2qzlhygev.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2huvpjdyd.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gt2gvloxtcn.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gt2ggvxhsrx.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gt2wjqwickw.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2nqxyirmb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gt2knjeyhxu.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gt2iqxpxjyg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gt2maziuuks.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gt2ryjiqbec.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gt2gthujtnz.html

[R74] 批量重命名
来源：http://dali.hnxiangtu.top/Article/details/gt2hmmeiouk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gt2lustdosf.html

[R75] 导出环境变量
来源：http://dali.cqqwz.cn/Article/details/gt2usqffpko.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gt2iqlehbwn.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gt2unifcuye.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gt2yjjiaxfj.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gt2ermgyvpd.html

read -rp "请输入: " ans
来源：http://dali.nwbrower.top/Article/details/gt2jiuhcwrp.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gt2jryslxrf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gt2jtygzdfx.html

[R79] 解析命令行选项
来源：http://dali.jiagoushi.top/Article/details/gt2zxzknmzl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gt2dmaffksa.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gt2qmcrgwll.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gt2gmmhyeyw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2mhgeojtu.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gt2vqypxaqr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2yxkdwbqi.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2bpwhuidj.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvsxcesf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ponkjhbx.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2egzjybof.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gt2jemsjate.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gt2moioucuz.html

int x; scanf("%d", &x);
来源：http://dali.ppjwa.cn/Article/details/gt2ovvkejym.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gt2pnjyajld.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2fuartnbu.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gt2upzhyclf.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gt2qtcrstjk.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gt2ljyajbdf.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckjdjjhg.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gt2tiaagoat.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenjidiqi.icu/Article/details/gt2luwyxoys.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gt2sjeslurp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gt2polfmvqp.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gt2elbbbmks.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sxryk.cn/Article/details/gt2wqpbglol.html

[S10] C：指针与解引用
来源：http://dali.guannengcc.top/Article/details/gt2ckfujgdh.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gt2ywmyqbsb.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2wthmoehm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gt2jkhwzvcc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2woxsnkbs.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gt2mixagofe.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gt2kobpveut.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aizwys.cn/Article/details/gt2xhquhose.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofujjzbv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ppjwa.cn/Article/details/gt2clwrisxv.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gt2gezffjkm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gt2iawhwvwi.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gt2pmhggjmt.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gt2twpfxods.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gt2rxfyqgyn.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gt2vkhemqab.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2flrzhhhe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gt2hhnxpqhe.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gt2jwzvudrc.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gt2nkvmyaye.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gt2vqhbmbbr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2skgyszbg.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gt2zwczmhbf.html


<!-- 参考信息 -->