代发 wailian999

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gt2tlmhhrzl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gt2zqehuolw.html

[Q45] EXISTS 判断存在
来源：http://dali.tian-w.cn/Article/details/gt2osqdmeux.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gt2txojpicc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gt2llixmkri.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivmhtize.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2usmyqysc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gt2zmblpgox.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2tszlkbtj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.316326.xyz/Article/details/gt2jarjhxav.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gt2edrhlbcb.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gt2mvssvwmy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2rxyjcxqc.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gt2bksgqzco.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gt2inytloqp.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gt2hlklbugr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obpafdps.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gt2qgliicca.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gt2rgxwthkg.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2envfhewf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.316326.xyz/Article/details/gt2utvybpmh.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gt2draxippg.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnswkylq.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gt2ozpwdaqz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gt2wuoqhgpf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gt2iparywnh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psvbudly.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gt2mmjhmnos.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thcbkgbb.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gt2keoggvkn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2ztixykhu.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gt2ybvdnekg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2jvkctbey.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gt2bnktjsjf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guannengcc.top/Article/details/gt2iwkysxql.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2arvvfltb.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gt2kcsjublu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2nbqdypcm.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gt2zhncverv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2sxklhxvt.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2duuhffkx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gt2eupbswji.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gt2sjbnbcql.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gt2tnhfsjpj.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gt2wbrmsplf.html

ROLLBACK;
来源：http://dali.gotoacloud.top/Article/details/gt2egdegefe.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gt2bhloxjay.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cashguo.top/Article/details/gt2xslqlrzc.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2miefsczh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gt2iigszjny.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gt2qtlwlwtf.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gt2bdqlhzpv.html

ROLLBACK TO sp1;
来源：http://dali.yj202588.top/Article/details/gt2zdzdltxg.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gt2bclsyfmy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gt2kajhlxkh.html

[Q70] 更新统计信息
来源：http://dali.yongpay.top/Article/details/gt2agjwlwzh.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gt2iwwbmyfd.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gt2bupsktye.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gt2jrsdwtux.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gt2meyvavjf.html

SHOW INDEX FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2wvrclexc.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gt2gzfisbap.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gt2eugjzitv.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gt2glixwqyt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gt2ioyblhtb.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2zcwtnbyk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2kbdxmlzc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gt2kleyizts.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gt2hvlhdhoo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wakygsyw.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gt2qqvlebfr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tanke756.top/Article/details/gt2shzmksmx.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzihiuwp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gt2fbrwsnns.html

[Q79] 字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gt2vcpcjhdw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gt2utylxysm.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gt2sjdbkhho.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2ffhxqrtg.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gt2prqqyxqt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2nlghiqgz.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gt2cfylhual.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2ipjxhnxl.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gt2xgxvypcq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2wfpfntqi.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gt2nqxzgbzk.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2tywrrevr.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gt2wntscrtb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gt2ejyxazfc.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gt2jnvgtrie.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhoulong.xyz/Article/details/gt2taynlkkn.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxxurcvk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qehwbzqx.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gt2hibzfmvz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gt2ykexmcym.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2wxvnkjcj.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gt2gwpvpknp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gt2rjdjlxkr.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gt2dekcqpzz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gt2hzowkpqq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zsvdhfud.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gt2davblbrj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2vbzhlyzc.html

[R01] shebang 与严格模式
来源：http://dali.sweek.top/Article/details/gt2ycvqpoqj.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gt2cufqjzuk.html

set -euo pipefail
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdvtiqov.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqilzunf.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtjdnbso.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gt2xpfyoris.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gt2mqsefnoq.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gt2phhwaeec.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dianchejie.cn/Article/details/gt2snysctdy.html

[R05] 参数默认值
来源：http://dali.yanxiufei.cn/Article/details/gt2nuralhvx.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gt2qysstjvc.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gt2nfmzhedc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2qxnicblt.html

[R07] if 判断文件
来源：http://dali.zhongyouzk.top/Article/details/gt2bmeyddul.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gt2aqitewrg.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gt2jxrwjnqd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gt2bfpsrwoh.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gt2fwpbanpg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2tlkeynov.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgqdlyf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmngpgyn.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gt2mmknkqid.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gt2cohdejqt.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnumvwcr.html

stop)  echo "停止" ;;
来源：http://dali.dashuyun.cn/Article/details/gt2ybtgajit.html

*)     echo "未知命令" ;;
来源：http://dali.xinyue.icu/Article/details/gt2qsqlludd.html

esac
来源：http://dali.gzhubu.top/Article/details/gt2mkpoljem.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gt2valgwchx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gt2fbmostmb.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gt2zentdsat.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gt2fnhpndsk.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gt2cltxbicd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gt2lxewuvgm.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2xhgbbzhv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258.top/Article/details/gt2mdthunhz.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gt2hewuudla.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gt2luvltocw.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcsxkutk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2uczasofa.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gt2rnaicemo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2ghjifnur.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gt2rikoackn.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srxzyksk.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gt2rkaqqcnw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gt2sbecuetj.html

[R21] 字符串长度
来源：http://dali.smart0.xyz/Article/details/gt2cqzxcrjp.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gt2yxsstjvt.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gt2uqkeoyuo.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2exytqauk.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2ovmpbnjz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xinyue.icu/Article/details/gt2zmmxejqi.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2ddydqyjm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daxiang520.top/Article/details/gt2bfsnunbv.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gt2rnunnypd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gt2wjbbwhux.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gt2wvxokwsk.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gt2rjazvwhc.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gt2bupijcxf.html

echo $((1 + 2 * 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbeydspa.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gt2owwcyxpo.html

echo "scale=2; 10/3" | bc
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgfdxrjj.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gt2idmmglfy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yonumen.top/Article/details/gt2ytqdhbwh.html

[R30] 函数返回状态码
来源：http://dali.xylfe.cn/Article/details/gt2lbwtjlzc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gt2zmtujgqr.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gt2cbaynmna.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gt2odzukwae.html

[R32] 参数个数校验
来源：http://dali.yuxming.cn/Article/details/gt2lvywnmmu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2zoslkvss.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gt2ysteqpyv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gt2wyluhvku.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gt2sdqtidpj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2swgwwghj.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gt2eydptrxc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gt2cwdmidfh.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gt2xkkomevq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gt2nxaxvdvk.html

[R37] 把输出赋给变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttnwcwfq.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gt2hsxordaz.html

[R38] 管道串联
来源：http://dali.nwbrower.top/Article/details/gt2odpnmfip.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gt2lvdojfym.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gt2phmsjtmu.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2ddqvdavs.html

[R40] 追加写日志
来源：http://dali.ybcxt.top/Article/details/gt2toztniuh.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gt2eprhpaff.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gt2uxvefibx.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2xozfokgp.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gt2ptzciosc.html

wc -l < a.txt
来源：http://dali.shuidangran.top/Article/details/gt2lkzouojg.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gt2bnbwfqpw.html

find . -name "*.log" -type f
来源：http://dali.xziqi.cn/Article/details/gt2ibjfucxm.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gt2tfcallly.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gt2gqjeuptz.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gt2cpdfhrcc.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gt2tygjhbrv.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gt2cqjxdtri.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gt2gkoiomdn.html

[R47] sed 单行替换
来源：http://dali.jinqigufen.top/Article/details/gt2txtbezit.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gt2efcowpjz.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gt2opaimkxp.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2wbqgpnfz.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gt2yjphegnt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gt2goemfyjm.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gt2uzgszbna.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2qijflswm.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gt2fiucaxvm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gt2zbjsqayd.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gt2dzcahbzh.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2xzgeoldj.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gt2dpiockbb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daxiang520.top/Article/details/gt2nggwpjsj.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gt2ijjqtyzt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvljduq.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gt2ghvvmeli.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cdnleiting.top/Article/details/gt2tarwspvo.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2aplzuzwb.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gt2lafjrguh.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gt2lsdnfcfk.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gt2jneomleh.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gt2okcjbhgz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gt2vudgksiu.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gt2fwucbecp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gt2gjzbcuzs.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2klqvnoua.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gt2jqsjqmxl.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyyeeqcp.html

df -h;  du -sh *
来源：http://dali.c1oappe.top/Article/details/gt2ppfsuuey.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gt2prdujkey.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gt2qpkqasxk.html

[R63] 内存与进程
来源：http://dali.feifeiyinyue.top/Article/details/gt2cvcrqvov.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gt2xlsigcbs.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gt2cveihrsh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gt2svjsnxxc.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbzmlper.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gt2etibwccw.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gt2pdppftxi.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gt2lstoogjf.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gt2ruwrlamp.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gt2wdxtbglp.html

[R68] 计算文件校验值
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnranojk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2vhunjtpe.html

[R69] 生成随机密码
来源：http://dali.sxryk.cn/Article/details/gt2qerdnhra.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gt2plxychhn.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gt2xnmgjzil.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gt2mrxqnwgo.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xylyswuw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gt2umrojwce.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gt2xhjashsx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gt2qbyugqbc.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gt2vbwodukc.html

split -l 1000 big.log part_
来源：http://dali.dashuyun.cn/Article/details/gt2iolclock.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aykpjczm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gt2oiyicuhc.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gt2dmupfpsy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gt2diuzhugr.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gt2shsjtqrp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gt2ucghbdry.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gt2fwkocbze.html

read -rp "请输入: " ans
来源：http://dali.sufxvd.cn/Article/details/gt2epvnkjpr.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqdqcpte.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gt2ewapmuhx.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gt2sdqgqcba.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gt2fvbpmaqz.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gt2byrqagti.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gt2vyqfhecv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2qwknyueq.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gt2qrchfmur.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2lzjqecrh.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2btsajrou.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gt2rlcoffdb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gt2omrsidaq.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gt2aahoddef.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gt2mgmeumqf.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gt2fitnddnt.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gt2busfvdvz.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gt2webyjdxh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2zubosrmp.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gt2ndxnwpiu.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gt2zepoigsj.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2dtnjczgf.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcqurrau.html

[S07] C：数组遍历求和
来源：http://dali.tanke756.top/Article/details/gt2enikbyeq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gt2igwkmdrs.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gt2culkqrei.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gt2tedhltgd.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqxhxcat.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gt2rhgrmuad.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gt2otcmusdy.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gt2ucupaxcx.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2atgetoxx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gt2brsvfuza.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.kuanghao11.cn/Article/details/gt2iovwzsja.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2uhremohe.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gt2dqtgivme.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gt2rxibjfao.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gt2bdobgqnf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258.top/Article/details/gt2dymugnvp.html

[S14] C：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwvrxmsl.html


<!-- 参考信息 -->