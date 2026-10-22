代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cucudq.cn/Article/details/gt2sbobjqpm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gsotkyqq.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gt2sslmcqxp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ologsyld.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gt2zjezhfos.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqicjqfo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gt2agcxiwhe.html

[Q49] 更新单行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhpoiefz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2skkmxftj.html

[Q50] 批量更新
来源：http://dali.aibaodan.cn/Article/details/gt2qnipxeor.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xylfe.cn/Article/details/gt2nultgtqw.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gt2onjehxri.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjvtyrba.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gt2ocashnmj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qppguxlx.html

[Q53] 按条件删除
来源：http://dali.jinqigufen.top/Article/details/gt2xfeuonmx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gt2jzeaejue.html

[Q54] 清空表
来源：http://dali.zhongyouzk.top/Article/details/gt2bcmqeicw.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gt2kuqxrwme.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gt2uhfcrlpe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258888.top/Article/details/gt2wiabuszh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gt2oofxdlqa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gt2tbzjdrks.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gt2fgwfzaro.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2elsigcgy.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sguvbjfl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2mmqeuvmm.html

[Q59] 分组内累计
来源：http://dali.hnqzz.top/Article/details/gt2quswqiwx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrkhtlsi.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gt2haphexoc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gt2grhxtdic.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2jwimnxzb.html

[Q61] 移动平均
来源：http://dali.kuanghao11.cn/Article/details/gt2cxqjitpw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2ddttalms.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gt2xwsyiztg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2oacmbwok.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gt2jkdanstr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gt2moadzlwj.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gt2wqhqzxkr.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gt2zwnafbew.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gt2xmhpjtjd.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cslugncd.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gt2erwaldps.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gt2pypbxhbd.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gt2znwjkhzw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.vqdsnc.cn/Article/details/gt2koaiiejg.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gt2djyxzybx.html

SAVEPOINT sp1;
来源：http://dali.hysaishi.cn/Article/details/gt2vqbmnryd.html

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gt2vbvtzkwb.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gt2idxugaze.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gt2mzdyikbb.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gt2qiplejfu.html

ANALYZE TABLE users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggltvrks.html

[Q71] 查看建表语句
来源：http://dali.pycfn.com/Article/details/gt2zvhnmugc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.meibo888.top/Article/details/gt2pjkiokyi.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2zefjekgs.html

SHOW INDEX FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrdlzhtz.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gt2bfylgmyh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2weuqvpin.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gt2cpdehokk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdolnugk.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxxbbcyw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2sdxjypbc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.meibo888.top/Article/details/gt2vbthjlgr.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gt2ttsjitas.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gt2idfdwgwf.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvjcnttz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gt2oochejbl.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbvkxmia.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gt2votyfznn.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2vtxfoaox.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gt2vqhirsfc.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gt2xwaafczy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2jcwtctsl.html

[Q81] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2yncepysv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2ahobwvzn.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxinkj.top/Article/details/gt2udegmtec.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2fgqyzcgv.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2uvnpycng.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2bneqxxsf.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gt2fswazixd.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2uddfmsvs.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwududpv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gt2smzmnshc.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gt2jjblskvh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.kuanghao11.cn/Article/details/gt2lxxeroed.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gt2daoxyvwu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gt2nzpuqypr.html

[Q88] 行转列（条件聚合）
来源：http://dali.316326.xyz/Article/details/gt2cabsrmle.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gt2muspvalw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2htntyknv.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gt2thcrxeqz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gt2hclgkigh.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gt2gtuorsjg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkycmred.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2amutjauo.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gt2tlhcdhmp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2sgyoxmey.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gt2kvpkcdmu.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gt2olxtyest.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gt2ohjxvpzz.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gt2vjqksiml.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gt2gjfvudho.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gt2pdfjotkv.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gt2thcrdrqe.html

[R04] 位置参数
来源：http://dali.cqqwz.cn/Article/details/gt2vovaiqab.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dianchejie.cn/Article/details/gt2lmydwyhq.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gt2nvoqwkot.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gt2gtjzrcnu.html

[R06] 判断命令是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2dibzppsw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gt2bjdndzds.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gt2yytzvjjg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2hifpulfy.html

[R08] 数值比较
来源：http://dali.vqdsnc.cn/Article/details/gt2kubefjqb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2ueuwffjc.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hkrsmzbg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gt2rpqwsoxb.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2brmubqjd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gt2hhpfdygw.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2guymamsi.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gt2rjyejvau.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gt2hqyqfght.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2kuqlauqf.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2nuionfsu.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gt2bdnvbxip.html

[R12] for 遍历文件
来源：http://dali.gzhubu.top/Article/details/gt2csokassb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ivvv.top/Article/details/gt2ijkepllc.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gt2kulodvbv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2qnpeqgpf.html

[R14] C 风格 for
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyqwjggi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gt2fxthenwc.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2jgqtgxjd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmdjzkac.html

[R16] until 等待条件
来源：http://dali.hammf.cn/Article/details/gt2xithwley.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gt2axekffoo.html

[R17] 数组定义与取值
来源：http://dali.dianchejie.cn/Article/details/gt2vjscwbws.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jlsjyb.cn/Article/details/gt2ltmxlufx.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gt2bpcfeilm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gt2jjswgdid.html

[R19] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2sfvdngle.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gt2jfkmypce.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gt2qalvtlxx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guannengcc.top/Article/details/gt2wzmyigae.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gt2vczlunwr.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gt2lacelwco.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gt2wnuxmumr.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gt2nqvkgwoc.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctepfnol.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gt2xffsefqz.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2ulbzmhdi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gt2mehwxhsu.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gt2luxbxuck.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gt2cnubpbgl.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gt2fdtqkxfy.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gt2aeyyybks.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gt2vfkjcyhk.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gt2phkfzpbr.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gt2aigcmnko.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gt2emfpdauj.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2gicwjzym.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gt2puauxlzf.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gt2rewzipqo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gt2kkfpviko.html

[R31] 局部变量
来源：http://dali.gogol.net.cn/Article/details/gt2jqfchnei.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigufen.top/Article/details/gt2bedzxfwp.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwyuibni.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gt2xhmjkxax.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gt2tzpxhjax.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gt2ttmbneja.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gt2oamgoizz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gt2otlskrcb.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2naycnrto.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.c1oappe.top/Article/details/gt2sdnhxlqk.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gt2rsnsnzbc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.haohaochexian.top/Article/details/gt2jhkzxpnm.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gt2obyyrpih.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2nlsbdond.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gt2cljaxwpa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gt2shbkksbs.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gt2kvwkppjs.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxdyhevj.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrnafhrz.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gt2fevjsnan.html

[R41] 丢弃输出
来源：http://dali.cdnleiting.top/Article/details/gt2lcpdbmxu.html

cmd >/dev/null 2>&1
来源：http://dali.fengsongda.top/Article/details/gt2woqcxeis.html

[R42] 输入重定向
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwxrbpwd.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gt2zcaefksu.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gt2ktchbymc.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gt2dpbicgoj.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gt2eftqvtfk.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gt2utplsnsc.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gt2ynulzyvn.html

find . -name "*.tmp" -delete
来源：http://dali.dianchejie.cn/Article/details/gt2osdgirfo.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gt2jfdrfffc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gt2yfrwqktq.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwleuiwp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2ndvohsoq.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gt2fnetijwu.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2ocqasdxu.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nkwesznd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2twfrqgrz.html

[R50] awk 求和
来源：http://dali.jiagoushi.top/Article/details/gt2rlgccjrg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2ybknuzuu.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gt2tpbxzmqz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gt2ncmgpspb.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gt2dlzhrsam.html

wc -l a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2pkjnzstz.html

[R53] 查看文件头与实时尾
来源：http://dali.cashguo.top/Article/details/gt2qdwxfoga.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gt2mqrjzoab.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gt2mzwukuxv.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdwxnrfe.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gt2uiqzdohc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gt2hnnehrls.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gt2fucoquqn.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gt2krcblldn.html

[R57] 远程执行命令
来源：http://dali.cdnleiting.top/Article/details/gt2owxbdsdr.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqlkwvez.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gt2zaaprabl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gt2seavmwpn.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gt2ljomdxdi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gt2dbhovyot.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gt2pszsduer.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylpfmzmi.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gt2wqpetjra.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gt2uwybxuzz.html

[R62] 找最占空间的文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvfansal.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gt2jngtcufe.html

[R63] 内存与进程
来源：http://dali.haohaochexian.top/Article/details/gt2koalaqeg.html

free -h;  ps aux | grep nginx
来源：http://dali.aizwys.cn/Article/details/gt2qfmhrthi.html

[R64] 结束进程
来源：http://dali.zhoulong.xyz/Article/details/gt2gllqrnje.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gt2caqfkbtj.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gt2ohkfvpeb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gt2mzzriybs.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gt2fydojlpb.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gt2jkjwxjbd.html

[R67] 生成随机十六进制串
来源：http://dali.sxryk.cn/Article/details/gt2iruwxmdv.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gt2lblteljz.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gt2gwqkipnt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gt2rnzsgwva.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gt2aadfjieg.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gt2xnxcmaqd.html

[R70] 时间戳与互转
来源：http://dali.yj202588.top/Article/details/gt2bynwermq.html

date +%s;  date -d @1700000000
来源：http://dali.cashguo.top/Article/details/gt2nwdvnabh.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gt2suihraic.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gt2vnoqbddp.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gt2farfgiwt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gt2vhrdxfua.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gt2qvmstxfg.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gt2pkjoifrn.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmzbiave.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gt2lnpqqbsf.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gt2mvborbqy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2dopsftpo.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gt2mornnudf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gt2xcynxvpq.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gt2buxvncvt.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gt2uhzucbvq.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gt2wxzjyoxc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gt2klporqns.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gt2gygkrmcf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gt2pbjjnhso.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gt2lbgxvyfr.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gt2nhbrurrk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evfvtbpv.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gt2bqvdziiu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ungtydod.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gt2ycjpslgr.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gt2hluiszgd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gt2xxvkikuy.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gt2jgwajouv.html

int a = 10; printf("%d\n", a);
来源：http://dali.jiagoushi.top/Article/details/gt2egqtujsx.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gt2dqiyniho.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gt2qcichumm.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvlhigsc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gt2ogcgpzem.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gt2rwfblrbc.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2grkicifd.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gt2plquqavn.html

strcmp(a, b) == 0
来源：http://dali.ivvv.top/Article/details/gt2piruqtdm.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gt2cdwfwbtj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gt2xcuaaohl.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gt2uxxjsrtq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tlchhepn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gt2bunbsntw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gt2tlofujeu.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gt2apxpuhpv.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gt2rgdsychp.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2ecfwxpfj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gt2xrpnmmtv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2foaddgav.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2jstxzgzl.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2ttkfqtgz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2ikkyxknh.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcffymla.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gt2pnrkvhsm.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gt2nmlibwfq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gt2awwbetor.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gt2vabdqjpg.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gt2vyhwndxq.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjmhmnna.html


<!-- 参考信息 -->