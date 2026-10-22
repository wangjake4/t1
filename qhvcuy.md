代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhixingplan.top/Article/details/gt2anjwudbd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jyoumei.cn/Article/details/gt2pdxaopdy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenzaomai.com/Article/details/gt2dxsgsvay.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gt2lwgzscpo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2acdrvnuz.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gt2iogrotrw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hyqbflct.html

[Q51] 用子查询更新
来源：http://dali.zhengqikj.top/Article/details/gt2snxfxkrm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2higjnhgc.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gt2toqyzfwh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2tbrwhfrw.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gt2lkdkplks.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gt2cwxpjbhi.html

[Q54] 清空表
来源：http://dali.yj202588.top/Article/details/gt2iwbdlclv.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gt2jlhunzbh.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixbrawrn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gt2uilstfea.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jyoumei.cn/Article/details/gt2yxqqiukp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gt2ykmqqdjo.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gt2iquefdeq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eewvkshz.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gt2wvrpydlq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2updqlaer.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gt2oounauin.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2ujpxeaic.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gt2trdykyry.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gt2veqxnubl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2cvcilieh.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gt2darlrzpj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kuadyopj.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gt2uwlftoyd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gt2opblbzjo.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gt2ltimqmiy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gt2jbgebwqc.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gt2ktkvugtk.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxdpanac.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gt2xqbslimh.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gt2tettufxg.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gt2arlcgwft.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daria6918.cn/Article/details/gt2gdsxwkcd.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gt2xmwwbyfd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gt2yjbfuaqs.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gt2hxdrsomv.html

SAVEPOINT sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2brufzpkw.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gt2gwuydqtu.html

[Q69] 查看执行计划
来源：http://dali.wangdashe.top/Article/details/gt2btfkiojg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gt2faisuyrh.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gt2aovrvekk.html

ANALYZE TABLE users;
来源：http://dali.0kj1m.cn/Article/details/gt2cxlcnbjl.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gt2uimyvzrj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yvedp.cn/Article/details/gt2uzabqhdn.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gt2amqlcolh.html

SHOW INDEX FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2evyhmgce.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gt2bmkewcca.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gt2xecmaoqh.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gt2kqhcqwzb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gt2wlmwgzau.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2edhqosro.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2cqqhcacv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gt2yyliblux.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gt2gfkppgku.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ybcxt.top/Article/details/gt2mewvdmji.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gt2xmtmggoh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gt2bwitoiaq.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obyqukle.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywvaquor.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gt2vnffvmec.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gt2hpqrvjee.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gt2jzqxdapg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2wqbhxlmy.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txibvudh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gt2qckqvhvd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gt2eiklyzrm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjyfsftg.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gt2nhuinqfh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2varpblce.html

[Q84] 去除首尾空格
来源：http://dali.pycfn.com/Article/details/gt2gqkbkaju.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2dgckvvjq.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gt2aeujsopz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gt2hwgawogt.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gt2xibliqcp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gt2cthhhiwx.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbefhaqo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gt2kqmfwoqn.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gt2ekbwofcj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gt2otxfpycj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2nxkjssjh.html

[Q89] 判断表是否存在
来源：http://dali.daria6918.cn/Article/details/gt2ytmitcan.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gt2amgfxxah.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gt2egstgraf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gt2gmugmmnt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2aowuenfo.html

R. Bash 专题
来源：http://dali.iojbl.cn/Article/details/gt2sfpiloge.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ncennhdv.html

[R01] shebang 与严格模式
来源：http://dali.ybcxt.top/Article/details/gt2ouxtxatb.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gt2dkdnybwp.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkvoukhh.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrwwvwwi.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gt2dfqrzynw.html

[R03] 只读变量
来源：http://dali.tian-w.cn/Article/details/gt2ulqhhxio.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gt2rzbqadjh.html

[R04] 位置参数
来源：http://dali.yanxiufei.cn/Article/details/gt2mijwoeza.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gt2syjlpmck.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gt2yegbjdqs.html

name="${1:-default}"
来源：http://dali.jqgufenzy.top/Article/details/gt2rduaxbgf.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gt2ncrqgawu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vymyxapx.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxyjnhoi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yyulduyu.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gt2shagoini.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2zntcured.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfnosgaq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2qabcqatx.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gt2cwgbudbq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gt2tyuhzwjb.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gt2hfnmqnif.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gt2weztnzmn.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gt2nyoxpdss.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gt2hipolmuu.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2tggvglaz.html

esac
来源：http://dali.yueranfly.top/Article/details/gt2znqizpyp.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gt2zgzzrsxi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gt2owokwcmu.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gt2xdibwhek.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gt2ghyglehc.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gt2iamrlziz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2dduvbuzx.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2carxkmnh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gt2jqpvtbra.html

[R16] until 等待条件
来源：http://dali.snrcjt.cn/Article/details/gt2fdfdidbi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gt2nrmmgebp.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gt2rkxayzrf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmafekla.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gt2uiztvqck.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gt2iepxrlax.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gt2nmxjjwnw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fajmmhti.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gt2azgzbmqg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gt2lcczyylu.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2ofdetcxx.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gt2txaidqty.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gt2htjctems.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gt2tzbczaul.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gt2kgsujyhd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gt2iaffcakv.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2bejlsbty.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gt2zcaqbsul.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gt2ahnhmhih.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gt2wbwzvnjz.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gt2dcapcmae.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gt2ufizadea.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfrhlwxr.html

echo $((1 + 2 * 3))
来源：http://dali.nanxuanxn.top/Article/details/gt2wfdpufgb.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gt2ynbamhfr.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gt2vyirpndi.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gt2jzrafoud.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sysykeji.top/Article/details/gt2ulhlytul.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gt2fsywatlt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gt2rglczlfw.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gt2vdurnsnt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wsrqcsnx.html

[R32] 参数个数校验
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxdbrbwm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gt2nswclhtc.html

[R33] 捕获错误并提示行号
来源：http://dali.haohaochexian.top/Article/details/gt2zxhlrpma.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daria6918.cn/Article/details/gt2ayrpwswm.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gt2jptltmbk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2cfrqysgv.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2alvakeqp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gt2iutkgwky.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gt2ijvzkdjf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzosuomw.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gt2rvbftsjp.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gt2yboxrztu.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gt2tvgohntw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gt2ivhobzga.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnekkyhh.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gt2sbuhcghh.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gt2jbdngslk.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gt2nxaxfnup.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gt2pqgppiwr.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2jrlicxws.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gt2zkabeian.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2zqobefsr.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2zindchtn.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gt2gdgicycm.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxbgmxky.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gt2cunxxhti.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gt2gxkzcuwb.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gt2rhxlxphx.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owbdgwhw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gt2gjcswrdh.html

[R47] sed 单行替换
来源：http://dali.fzhhl.top/Article/details/gt2lrcuqvkj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2aidvwyci.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gt2lcexecim.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2ddylmclr.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gt2ivrixiha.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gt2xfsburdb.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gt2sekolmei.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2fnhuuqwm.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdmulhva.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fzhhl.top/Article/details/gt2bdnvpdsl.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ziditeyx.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2gkcsamli.html

[R53] 查看文件头与实时尾
来源：http://dali.zhongyouzk.top/Article/details/gt2qrvteroj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gt2qrmqemkt.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gt2xjvdhioc.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gt2klxtjodx.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gt2clqiaqlk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gt2ulrbgjad.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gt2gaupsewi.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gt2hhnjaleq.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gt2hapgdlic.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gt2mabzsnij.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gt2nmunrpqa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gt2hmtdykkv.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cobjdmqi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gt2yztgxrws.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gt2wifsaguk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gt2jdgjarou.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gt2ylxlbqso.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gt2qucitjki.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gt2ttichuqf.html

du -ah . | sort -rh | head -10
来源：http://dali.andypj.xyz/Article/details/gt2yrdsgwbi.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gt2vdlmwxar.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2oisseoom.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gt2plgksmkx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gt2wrrkwumv.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gt2vtffpviw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gt2ansfvanq.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uiuvmigc.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gt2glqilinc.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gt2ndmvmwhn.html

openssl rand -hex 16
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bigqcjjv.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gt2dxbccdms.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2qkgfyxkb.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gt2qmklebpj.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gt2baqweadw.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2vsfqkqei.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zblhncsz.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2rktkpkaj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pengpengdd.cyou/Article/details/gt2upsabwea.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gt2ypakkytl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gt2mrikylrt.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gt2fzcfvymk.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gt2kbbfypju.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnxycbpd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gt2xkrwikyx.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gt2ftygosux.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gt2vrqtqbpk.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2raogiryt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gt2dyehospg.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkfbepts.html

read -rp "请输入: " ans
来源：http://dali.aizwys.cn/Article/details/gt2jgjmdlou.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gt2fpkpiusl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gogol.net.cn/Article/details/gt2qiagsuwq.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gt2ecyhkzhd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gt2ebniyegp.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gt2rebhfarx.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gt2htcenctk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2yavvlzmh.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gt2ofdwbvob.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2zdrhpnjc.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2qcksyuuy.html

#include <stdio.h>
来源：http://dali.ydzc1.top/Article/details/gt2msayntrv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj202588.top/Article/details/gt2eatpjxem.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gt2hrwgudak.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xyhiahag.html

[S03] C：读入整数
来源：http://dali.sxryk.cn/Article/details/gt2bmwsrugc.html

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gt2mrtvtntn.html

[S04] C：字符串复制
来源：http://dali.zhongyouzk.top/Article/details/gt2zgbqlian.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2gounfpkc.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2tutyqcgi.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gt2qqzuhbiy.html

[S06] C：字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqfereqm.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gt2cidfawuo.html

[S07] C：数组遍历求和
来源：http://dali.hywenlv.cn/Article/details/gt2ixcnfcaj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gt2cwdsjrkg.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gt2idejvojt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gt2cghmwnwl.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpohynyj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.bjfxy.top/Article/details/gt2phjmqfuw.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btwoblpm.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gt2chzigbur.html

[S11] C：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2eqthxpsl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gt2gpgcnmbw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.svipenyu.cn/Article/details/gt2tpphavhb.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2edvnkhso.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2argszwoe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gt2vegrljmf.html

[S13] C：宏定义
来源：http://dali.tian-w.cn/Article/details/gt2xywjsraa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.smart0.xyz/Article/details/gt2dzullaom.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2cdxwhwob.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gt2veyuwshx.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gt2gauvpxvp.html

(double) a / b
来源：http://dali.chenzaomai.com/Article/details/gt2egzkzcrj.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gt2xypgzlss.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gt2xbtgxbvj.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2indktgtn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gt2bbockdoz.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gt2voegchsv.html


<!-- 参考信息 -->