代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.xziqi.cn/Article/details/gt2ryksgxzk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gt2lzdwtkgu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gt2quunqhty.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gt2wwnicjzx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdlzkrbj.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gt2ggkfpblx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gt2eyxnpigm.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gt2pvuuwiat.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2oanuowzw.html

[Q52] 删除指定行
来源：http://dali.hfpthk.cn/Article/details/gt2vuyiidia.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2utjgdbfr.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gt2nkwhfpur.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.9152youxi.cn/Article/details/gt2nlvevnug.html

[Q54] 清空表
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrzqbwng.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gt2pyjsycsc.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gt2rjnpnykk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gt2qpnzcybx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gt2hjifzbvc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gt2piqtjwzg.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gt2znbfjnkx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2wjlpoini.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gt2zhmwldjy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2aiiezqpj.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gt2hlyozgei.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwpqpwht.html

[Q60] 取上一行 / 下一行
来源：http://dali.ppjwa.cn/Article/details/gt2vawpfpkc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuxming.cn/Article/details/gt2benuodjz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2mniaejuk.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gt2yakrmoxm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2nmhjhqbt.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gt2udbhejsg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2khcabwrv.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihruolfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gt2wjdczovs.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gt2gnkgazzx.html

COMMIT;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrvlqghd.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gt2wlibkuhr.html

ROLLBACK;
来源：http://dali.fengsongda.top/Article/details/gt2oqvxbegg.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gt2nrgepewe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gt2enicbrqr.html

[Q67] 设置隔离级别
来源：http://dali.sxryk.cn/Article/details/gt2tcbqoujm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdabkgtb.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gt2kybugcvz.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gt2wxqokwvm.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gt2zyoiojeh.html

[Q69] 查看执行计划
来源：http://dali.hfpthk.cn/Article/details/gt2txibpoop.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hysaishi.cn/Article/details/gt2ynmpilop.html

[Q70] 更新统计信息
来源：http://dali.yonumen.top/Article/details/gt2lmrpxgbj.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gt2srytmqzx.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gt2awavxrup.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gt2qgcgilkl.html

[Q72] 查看索引
来源：http://dali.dianchejie.cn/Article/details/gt2mbmxvbdz.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2vfjrbnnv.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gt2ddamuvpf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gt2imzopfez.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2glfpqohu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gt2nmrwrjat.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gt2mgyzgxlf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2khasojec.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fcxfsegh.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2auatvaqo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gt2pdumsavu.html

[Q77] 时间加减
来源：http://dali.quarkkingdee.top/Article/details/gt2mxaywbjg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangdashe.top/Article/details/gt2xgxapxkb.html

[Q78] 当前时间
来源：http://dali.cdnleiting.top/Article/details/gt2murbgniw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gt2avvtqlop.html

[Q79] 字符串拼接
来源：http://dali.ybcxt.top/Article/details/gt2wcrficcs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqufumjd.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gt2dfozpvft.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2ndlxhpfy.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2hlhwqgrp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2lhjgnjgz.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gt2oziusgoy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2divqfhme.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gt2agbclhrf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2jaslsybd.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gt2vfddcqhn.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2sgqqzdeq.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfhdhbof.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gt2klmnoecv.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2lddggckx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gt2kcjnwobn.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gt2wsqkixce.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gt2wtdhvcok.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gt2tgrqzizk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxchuzi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2vnqwrajc.html

[Q89] 判断表是否存在
来源：http://dali.zdqjudy.top/Article/details/gt2ojwphmco.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yvedp.cn/Article/details/gt2xwdmjtbe.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gt2nkqoycix.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gt2bkvnaqdv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2cygalvam.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gt2cjqpaxxs.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2yrtgkown.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gt2ztmzouwv.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gt2txbmevoi.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gt2dqobqctb.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gt2goujtvst.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gt2bmbpvtbk.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gt2bmmhsuwa.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gt2kwnevffv.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gt2ykcvipzn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gt2wgekznwa.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gt2sbjsfimo.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahwbkcqv.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gt2flkbmmiv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gt2dnjllzno.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yniolhoy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gt2gzbvslwv.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gt2grrpucnn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sstyizoh.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gt2zxqhtakf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gt2qfabhwcd.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gt2zqnjqhcy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gt2sbfcykac.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gt2zbejobdb.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gt2ifxfpmpk.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gt2uumfufyg.html

stop)  echo "停止" ;;
来源：http://dali.vqdsnc.cn/Article/details/gt2uyvfqegp.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2qilqgbcj.html

esac
来源：http://dali.hammf.cn/Article/details/gt2ewjjedfr.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gt2xvbtupnw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gt2drsaajko.html

[R13] for 计数循环
来源：http://dali.sweek.top/Article/details/gt2qlttvkyv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2wagdbgai.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gt2jkpushyp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2wdcdsqxz.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2xpxwainv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gt2tgjlfhoq.html

[R16] until 等待条件
来源：http://dali.yongpay.top/Article/details/gt2gwzhxnws.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gt2bidrzbbm.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gt2vwzhvjhr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gt2cweoonff.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gt2vzsooopa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2nplarqir.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gt2qzicibyq.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gt2rygrxceq.html

[R20] 关联数组（字典）
来源：http://dali.kuanghao11.cn/Article/details/gt2aetlaogk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfghqteq.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gt2ertcpmaw.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gt2ltrglyyg.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2ihomegfb.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gt2ahkjncll.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gt2wxsvfyjp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbherlvr.html

[R24] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gt2lbvrofir.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gt2ggjanchv.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gt2dlceeswy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gt2thseklyo.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezxffjeb.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gt2pwtluvhd.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gt2hixhujyo.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gt2comzdass.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gt2ubltiuoa.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gt2houumtaf.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gt2yseaxyqh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gt2lvbnccak.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gt2zhguzttr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gt2xffhcyxp.html

[R31] 局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jymswoby.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gt2gsijlpze.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gt2cgtfmluw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gt2pqdvdnxc.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gt2nwmruqdn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gt2klnjrkvf.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gt2uuplaapr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2nnhpsjio.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gt2oxmjyhyu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gt2ybadgzgu.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gt2reiqpzot.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gt2oltrkkdy.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gt2vvjwqpww.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gt2hvunrqvk.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwiwqown.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gt2jegosxhb.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gt2njwevjge.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gt2aunfsdvg.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msqlwtdf.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gt2ynzdnhje.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gt2ucqhchlg.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gt2xhzaayho.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gt2tedlfdqk.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2wlfysjqh.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypmbydjw.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gt2gkanyywp.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gt2jsrhpbpd.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gt2gffpkpqh.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzrmzjck.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gt2majlskme.html

[R46] 递归替换文件内容
来源：http://dali.gogol.net.cn/Article/details/gt2eacoyrwc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gt2mseqkrqx.html

[R47] sed 单行替换
来源：http://dali.gaohongyu789.top/Article/details/gt2iwllnjhr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2cnixqsuv.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gt2yypfjflp.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2acnkwofj.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gt2ksfvordu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cdnleiting.top/Article/details/gt2lmpwdokb.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gt2ptohfjzb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2hvwlwcxz.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gt2ddyyhvrc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tanke756.top/Article/details/gt2dbuopvqd.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gt2kuhgwahv.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gt2onzxpncc.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rkrpcycb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fshwzsxv.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gt2skszyitx.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2gostkrcf.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gt2vjysalix.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdepzkpk.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gt2pzsqoyjg.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gt2clchgxju.html

[R57] 远程执行命令
来源：http://dali.sxryk.cn/Article/details/gt2jgswmihn.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gt2vgcmumck.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gt2bhmqnmab.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gt2sftwwlyh.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2hwkbwhzb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhixingplan.top/Article/details/gt2qudrzpov.html

[R60] 只看 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gt2phqbqccq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gt2kaqjpnpj.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gt2sykchzko.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gt2ywzvwwca.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gt2oeyruzrf.html

du -ah . | sort -rh | head -10
来源：http://dali.svipenyu.cn/Article/details/gt2pivoepcm.html

[R63] 内存与进程
来源：http://dali.snrcjt.cn/Article/details/gt2ahzdgvhf.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gt2terbfpao.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gt2chtpojgd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gt2tvhkrseq.html

[R65] 查看端口占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqkvvyel.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gt2jfvkmoij.html

[R66] 定时任务
来源：http://dali.hammf.cn/Article/details/gt2seavujqf.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gt2olyyanjx.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gt2lblezcsh.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gt2websttbv.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gt2mdpucjhx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2ehrzsugy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeifbwm.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnqzz.top/Article/details/gt2doenezuh.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gt2rqndkxdq.html

date +%s;  date -d @1700000000
来源：http://dali.havefunace.top/Article/details/gt2joqfrgkw.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gt2kyhmpxrb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gt2ddmoskaf.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gt2shqpzcpx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gt2qrvhqdrs.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gt2gemzekwb.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gt2hqqzdzhd.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gt2bipouypf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daria6918.cn/Article/details/gt2zfgvxffs.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2skadicnv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hammf.cn/Article/details/gt2wdaeirxs.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gt2pzihmvyj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gt2gtyebrhu.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gt2yzpaqbln.html

read -rp "请输入: " ans
来源：http://dali.hysaishi.cn/Article/details/gt2mwzmjyph.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gt2espddmdx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utptgbop.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gt2nyvfqbhg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gt2obzunriz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhavlicd.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlxllgxb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2sthosxgw.html

S. C / C++ 专题
来源：http://dali.jiagoushi.top/Article/details/gt2udciwocw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2knkzqgwt.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2mzrqykwn.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gt2zuhyitnh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gt2izcsdaxq.html

[S02] C：变量与格式化输出
来源：http://dali.xinyue.icu/Article/details/gt2stsnxezr.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gt2gfpaezjm.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gt2wdchlror.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gt2oeezdjpb.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gt2vmaxzivf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2szghajjw.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gt2klomvpke.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gt2kpyqlcig.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gt2zxkudfda.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gt2ogmqpcdt.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwpfsiwv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gt2myhpqgag.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gt2pqsaovig.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gt2bdibmcla.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gt2tffsxpyn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkxzcsts.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gt2lqgekniv.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gt2yikkwpvx.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2wzhumqrz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gt2wtnrzpqt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2lontkqba.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gt2bpobawjb.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2rhlchduq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2mqxmwves.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gt2rfpzrudw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gt2yvvnulkk.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gt2kfdeaydz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gt2yqloeafu.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gt2blfbkmvg.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gt2zkzbrhpc.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbsacigq.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gt2sddbaazd.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2skbeyodg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tian-w.cn/Article/details/gt2yiuljqhu.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2qlkwjomd.html


<!-- 参考信息 -->