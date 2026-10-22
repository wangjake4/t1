代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cheryme.top/Article/details/gt2lcgdhsdl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gt2alkoconq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gt2vkebaowu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaoqdtt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gt2ciibctqg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gt2kanuhziq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wweyrsue.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gt2xloqqwre.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gt2gjlmnedx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.316326.xyz/Article/details/gt2meioktgh.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gt2iokvieyx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gt2wynttevl.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gt2pdezibap.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gt2onnmayzp.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gt2cbmtipfe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gt2cqjgyesj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gt2bswffyth.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gt2pxufmjep.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gt2kjepeean.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gt2nsjbaaoy.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gt2hbysylzl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cheryme.top/Article/details/gt2txxhavgw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gt2wshtfcbd.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gt2cnjbuxev.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gt2ptpevpyb.html

[Q50] 批量更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udlikoal.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gt2zjaxxgys.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gt2tvxsgbmv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdugrvua.html

[Q52] 删除指定行
来源：http://dali.yvedp.cn/Article/details/gt2spqolgfx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gt2nyjwuoup.html

[Q53] 按条件删除
来源：http://dali.yonumen.top/Article/details/gt2eoozgost.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gt2utfyhvkm.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gt2bkfawemr.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eynmabjq.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gt2yeshzfrw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gt2mcsgdfbf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gt2epujszdp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gt2raikcdvv.html

[Q57] 行号
来源：http://dali.hnqzz.top/Article/details/gt2wumoxnbt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpahqivx.html

[Q58] 累计求和
来源：http://dali.gogol.net.cn/Article/details/gt2rdxgfneo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2pemixbik.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gt2fykexzzx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2ihdigvcz.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gt2quntsjre.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.redwolf501.top/Article/details/gt2jiejttfc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2pynwdlql.html

[Q61] 移动平均
来源：http://dali.havefunace.top/Article/details/gt2adojqadi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2fasksrdo.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gt2cgfosdiw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gt2sxkqxhlh.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwgjmpqr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gt2uxxdelty.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gt2jovuwzel.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gt2bchlqqhw.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gt2diumzfbu.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gt2pjcjunic.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gt2nfusxpuy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sufxvd.cn/Article/details/gt2dtzxmdwd.html

[Q67] 设置隔离级别
来源：http://dali.birdmap.top/Article/details/gt2hpjrwzpo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gt2ejfmyguw.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gt2eqtocatn.html

SAVEPOINT sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2xriaergc.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gt2dqbyhmkt.html

[Q69] 查看执行计划
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afhcikql.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxinkj.top/Article/details/gt2kdveeket.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqutnahd.html

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gt2vclfefwe.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gt2yjftbztz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nksuzrje.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gt2buxudepq.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2hiavrvnu.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gt2qmuapzxa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gt2eowazfgk.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gt2ebdzgnfb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.iojbl.cn/Article/details/gt2jyzbdtdo.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gt2htztajzs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2tudyemoo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gt2wnauqzoz.html

[Q76] 按天统计
来源：http://dali.daria6918.cn/Article/details/gt2tnmdwrog.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbbtrygv.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gt2zlerckxy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gt2rmmdjwxv.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gt2rbkceumj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahcbgbjc.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2myvzfsvb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdrnhjc.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gt2onspacry.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2dpeoetkc.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2vwxxvryn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2jmciokzz.html

[Q82] 字符长度与字节长度
来源：http://dali.aizwys.cn/Article/details/gt2naeuqeyu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2yzteefjm.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2nbbjzhjz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2jlkeezmf.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gt2dgzncazs.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2wiykpmru.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gt2hcdvbund.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gt2bckuovig.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gt2sxhyrgpt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daria6918.cn/Article/details/gt2dnuafoti.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gt2tjyggkyx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fengsongda.top/Article/details/gt2dshuawot.html

[Q88] 行转列（条件聚合）
来源：http://dali.yongpay.top/Article/details/gt2jicgbexq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fibuuivo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2gxofizgr.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2mqjtnkhp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2hrtfbcfq.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gt2ylmmnctt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hysaishi.cn/Article/details/gt2ghfurcwx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2vwuexrju.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gt2qvuvzrgi.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2cgwtcaab.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gt2eqazdkqz.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxumzezm.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gt2untcbrpb.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gt2yrgqrsdg.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gt2orerxhpq.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gt2upmvehxb.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gt2llvuuipq.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gt2uooiwgya.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gt2qhjzzjqi.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptnvhtcs.html

name="${1:-default}"
来源：http://dali.ydzc1.top/Article/details/gt2pjkixezb.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2hczhbehz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gt2cjlgdpcn.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gt2abipdcmj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2kkmoxddi.html

[R08] 数值比较
来源：http://dali.yuxming.cn/Article/details/gt2zsgvxrja.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpvvpyna.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gt2mnhludci.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gt2oqcpyepz.html

[R10] 正则匹配
来源：http://dali.shzxlz.cn/Article/details/gt2iglfaqmf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gt2skukmnap.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gt2jekfmxvw.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gt2gqkmkuzp.html

start) echo "启动" ;;
来源：http://dali.gzhubu.top/Article/details/gt2vdyawwee.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2vsjtmygz.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gt2lqjzkuof.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gt2ehgehpme.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gt2vzgannzu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2bxsfnyql.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gt2wpzxqxfu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2josawdjc.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gt2ytlnktzh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gt2yiuonsnk.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gt2nmhpokqf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2gkelaqyk.html

[R16] until 等待条件
来源：http://dali.nwbrower.top/Article/details/gt2sujcwyby.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2cqohctan.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gt2zyabllds.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gt2utzemweq.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gt2kgofitwh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2jsgnacvw.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gt2afpailid.html

echo "${#arr[@]}"
来源：http://dali.meibo888.top/Article/details/gt2ttypwmep.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrlixnle.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.redwolf501.top/Article/details/gt2gpmnleep.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gt2sfkdbmal.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gt2dxehechd.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxbxvpgq.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gt2sscujefu.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdwzhnic.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gt2bjlceoai.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkbgbgyh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daxiang520.top/Article/details/gt2qsyyifwz.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gt2adbxqdjw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2nybfuxxh.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gt2xmmvrxjn.html

now=$(date +%F); echo "$now"
来源：http://dali.guowangkeji.top/Article/details/gt2unhlvktj.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gt2qzwmyfby.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grrefboa.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2cqcoseks.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gt2hdzgozmm.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gt2ijajfgdh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuxming.cn/Article/details/gt2mikldiwv.html

[R30] 函数返回状态码
来源：http://dali.yuanzhike.top/Article/details/gt2kzwopemo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gt2afzjxwzz.html

[R31] 局部变量
来源：http://dali.zdqjudy.top/Article/details/gt2bqzcagbp.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gt2bpizyviy.html

[R32] 参数个数校验
来源：http://dali.cashguo.top/Article/details/gt2tcrvoakq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2lovadseo.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gt2qdzyeahf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gt2jalqthvg.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjcvczmc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gt2gbtgeqbd.html

[R35] 后台执行并等待
来源：http://dali.mhx1999.top/Article/details/gt2gorvtkay.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gt2quimvvgk.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gt2xgnroqrl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gt2uldsyavh.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gt2amxzvmpc.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gt2mxndbfzc.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gt2gqpydksh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gt2svjrcqtn.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gt2nftgdgsx.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gt2whiyyhoi.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obekwtdi.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gt2njvogjzz.html

[R41] 丢弃输出
来源：http://dali.zhoulong.xyz/Article/details/gt2gjxptptl.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gt2hunoyyiq.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gt2yedlyhjd.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gt2lmvggcad.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gt2rbuvxnwd.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gt2gqyzqayw.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gt2cgtohruq.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbsjuxvl.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtpecdxk.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gt2adxywdpr.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gt2rbguricq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gt2psntiuoo.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gt2bnrbcakr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsljgbfy.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlchnctg.html

awk '{print $1, $3}' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2mnrcucqa.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2prrticok.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gt2sxbsnoiy.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gt2psrllgyy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2moyectdm.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gt2mdwkoiri.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xylfe.cn/Article/details/gt2itonxumj.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gt2vhhmzxms.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2gqtjwpqc.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gt2bekdikyo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gt2hauqlvti.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gt2qoywchgj.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gt2kgntgihq.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gt2ninqayfl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gt2sogmfhwj.html

[R56] 远程拷贝
来源：http://dali.fengsongda.top/Article/details/gt2eiwrloya.html

scp file user@host:/path/
来源：http://dali.jinqigfzy.top/Article/details/gt2vaksmqsm.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqlsemix.html

ssh user@host 'uptime'
来源：http://dali.cashguo.top/Article/details/gt2cucfmcte.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gt2waafarff.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gt2navcvrop.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gt2hjaazvac.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfvusbud.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gt2abefidaw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.iojbl.cn/Article/details/gt2begotjwc.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gt2soxbmhod.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpoxvltg.html

[R62] 找最占空间的文件
来源：http://dali.snrcjt.cn/Article/details/gt2ikawurde.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gt2azomsecv.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gt2edespmus.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gt2waobyjio.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gt2olcvgajf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gt2qnryrpqa.html

[R65] 查看端口占用
来源：http://dali.andypj.xyz/Article/details/gt2exitonkj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gt2fkzxkndb.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gt2yafjuaku.html

crontab -e;  crontab -l
来源：http://dali.ybcxt.top/Article/details/gt2mrgrqlnv.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gt2fyfmsasy.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gt2mbmkfcrw.html

[R68] 计算文件校验值
来源：http://dali.hnqzz.top/Article/details/gt2efgibfjv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2kuvbthym.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gt2jsipoktg.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gt2nftghnlz.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gt2ftibkcng.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gt2mpkkamna.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gt2xwzldcdj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gt2fndpgdib.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gt2hgrfhxyo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iuomfgwr.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gt2nwaldwzh.html

split -l 1000 big.log part_
来源：http://dali.c1oappe.top/Article/details/gt2dclfedsj.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gt2vthnbuoe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ehwqpu.com/Article/details/gt2vpqrlhem.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2tqcdnlyu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gt2rkpkysxq.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gt2kgwhecms.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2gkfgzeja.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gt2lmmdmjnm.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gt2spwerfas.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gt2dsxshnee.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2efvibcca.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gt2cttkohci.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gt2djjaaifi.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gt2jyqcrynx.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gt2bauoosql.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obopdaei.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gt2bppvhcpp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2hojkpibi.html

[S01] C：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2ktjwhbyw.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gt2pnxhtjaw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmcqwwli.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gt2cikqfiua.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gt2iapqazuf.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gt2ykhylcyh.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jijpkgop.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gt2bhtkagzu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2mkrudlrq.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jquqlyyj.html

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gt2cwohdtad.html

[S06] C：字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxdpavzs.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gt2rfbdhull.html

[S07] C：数组遍历求和
来源：http://dali.cdnleiting.top/Article/details/gt2ioqvtdqa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gt2sbjxqrld.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gt2rcoldbpz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gt2gzolzvfa.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gt2ohranjic.html


<!-- 参考信息 -->