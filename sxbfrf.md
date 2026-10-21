代发 wailian999

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gtxtadgogu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gtayhvylpa.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdidrhkcp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gtfnatbcsx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gtqqxpxdmm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtlzggllnb.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtatkdsjqb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gtlteutkuw.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtdxutwbrg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gtnedmpdvf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gttgrzsbny.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gtubkhcgtt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtxiqjqfqt.html

[Q50] 批量更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumttddrb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtuyboihyl.html

[Q51] 用子查询更新
来源：http://dali.ivvv.top/Article/details/gtnhxdbvmx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.birdmap.top/Article/details/gtmvjkdznm.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gtzupdirqk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtqcnziamk.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gtmkiseheg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gtrxvtkcrw.html

[Q54] 清空表
来源：http://dali.jiagoushi.top/Article/details/gtnbgwrheh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtjptqgwcz.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gtqlwmjzsw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtmeqphwzh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sysykeji.top/Article/details/gtpnfkrkpa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtwlpvjqfa.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gtaoseaqtg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gttdjfiury.html

[Q58] 累计求和
来源：http://dali.tianlin.xyz/Article/details/gtoolzuapb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtkkzfwtxq.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gtxsjanlpe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfyzijyw.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gthnnbvqhi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gtyccwxyox.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtpzoluguj.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gtajdmubih.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtkvoysmfh.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gthinawbal.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtzvxcvulx.html

[Q63] 开启事务
来源：http://dali.ehwqpu.com/Article/details/gtoxfirulv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gtsbcqgkpy.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmrlqlmd.html

COMMIT;
来源：http://dali.jlsjyb.cn/Article/details/gtfeefthfz.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gtgdhtoiom.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gtebejbljb.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gtwspkynwc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmpebqzl.html

[Q67] 设置隔离级别
来源：http://dali.yj202588.top/Article/details/gtssbyboal.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gtrmpfjjyv.html

[Q68] 保存点
来源：http://dali.gogol.net.cn/Article/details/gtauvmpzvx.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtlrmyvkbc.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gtzgszbpwr.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplmtwiso.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxinkj.top/Article/details/gtipnopskb.html

[Q70] 更新统计信息
来源：http://dali.redwolf501.top/Article/details/gtfrhpkrgx.html

ANALYZE TABLE users;
来源：http://dali.cdnleiting.top/Article/details/gtkwpocxmy.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gthyyojvew.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gtxtzqffhk.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtqbvuufnj.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtzhlheuuo.html

[Q73] 查看表状态
来源：http://dali.tian-w.cn/Article/details/gtqswnitnc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gtzemwrfdm.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gtyuwmeoil.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gtymxgohvz.html

[Q75] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtfrsjgeau.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtrhtqmsgm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtwytnqsrb.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gtlusmcxca.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ybcxt.top/Article/details/gthdvtntbn.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gtvhhafump.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gtgydjmnwg.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gtyipofehj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gtdkutgjps.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtvprrrrwt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gtuqgtfyfk.html

[Q80] 字符串截取
来源：http://dali.yj20258.top/Article/details/gtjjcfeucy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtvshfoibp.html

[Q81] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtlngxfyyn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gtvutgdhij.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gtqlngdoll.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtcaexzfyx.html

[Q83] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtcgkzyfso.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtddlpsdug.html

[Q84] 去除首尾空格
来源：http://dali.gzhubu.top/Article/details/gtkbonwtsb.html

SELECT TRIM(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtoknzkkaz.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gtbpweqrju.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtxzqnbohc.html

[Q86] 读取 JSON 字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtzgyzfr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gtgykcwule.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtertdtuby.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgradrmxa.html

[Q88] 行转列（条件聚合）
来源：http://dali.xinyue.icu/Article/details/gtazswpyfs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sxryk.cn/Article/details/gtnllehran.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gthpzcafun.html

[Q89] 判断表是否存在
来源：http://dali.cdnleiting.top/Article/details/gtnoobaqrt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtodwwxsih.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gthfqdlagf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnppaabz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtnkblptag.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gtbvxisbxg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtapcfqeon.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtrzmzplbk.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gtctwslfjg.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtlrfyttno.html

[R02] 变量赋值与使用
来源：http://dali.316326.xyz/Article/details/gtvqtzcohz.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtdlgzhryw.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtejrtlphg.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gthwgivwji.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gtsobdsvuj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gttmnshwow.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtydrnodjq.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gtoiuudier.html

[R06] 判断命令是否存在
来源：http://dali.yangfankeji.com/Article/details/gtyjcigqfz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtajejsjyb.html

[R07] if 判断文件
来源：http://dali.cdnleiting.top/Article/details/gttaretlbr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gtpmaknrub.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtuanayglt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtpifeagxl.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gtpsagwbdn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtevoexjju.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gttpqawony.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gtwryuaidn.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtgtkedugi.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbifmmnvu.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gtbthupuib.html

stop)  echo "停止" ;;
来源：http://dali.fengsongda.top/Article/details/gtppkogzug.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtbpvtxqmm.html

esac
来源：http://dali.zycfv.cn/Article/details/gtcphbmezo.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gtvmffwxhz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gtqzbsgwow.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtqdrqicko.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtgytksnxt.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gtctcfcpoh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtldyqenyp.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtxvmbaxrp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxuanxn.top/Article/details/gttvxtfheo.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gtdfbqqfdd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtxwmhmzre.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gtzczbeusm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtlulkxsbr.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gtbihaevts.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gtjfgxrhit.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtkhdrstxw.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gttwcwygkx.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gtttdavomp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtrezlqmhw.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtpofigkwx.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gtbcxquxwv.html

[R22] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtjuyyqpfg.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gtyewwrqjk.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxpjgrjs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtaibdavfv.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtpckikiyn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtzmxwrzcl.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gtnkprghee.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtxzoxkrio.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gtjgssiskl.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtgpakjbfy.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gtirkhnrlw.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtszqlokea.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttaiqhnt.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtcstozhfc.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtzcfbfxye.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtivtlzclt.html

[R30] 函数返回状态码
来源：http://dali.sysykeji.top/Article/details/gtupdgcsuc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gtcbzqdjtc.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gteiswcnem.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtsdxhfxsc.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtvyvsbalo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgewbzveq.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gtroeqezij.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gtniozfdvs.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gttyfwrzua.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtmhlnyanz.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnvywobt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenjidiqi.icu/Article/details/gtvwedfxcr.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gtesytqgvb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gtoyjrylib.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gttvmfexbr.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gtfhuatbqb.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gtwfiktgyg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gtdsoxywoi.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gtwyfuccgx.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gtyzbcupip.html

[R40] 追加写日志
来源：http://dali.yj202588.top/Article/details/gtoqqdmslc.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gtfvrbosyp.html

[R41] 丢弃输出
来源：http://dali.zycfv.cn/Article/details/gtxqwyltvo.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtzymisjdt.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtqrdpvzig.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gtjlrypxnr.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gtlndexnbm.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtnyqwdmns.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gtipqqumfx.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gtuzsbcoeh.html

[R45] 批量删除
来源：http://dali.ppjwa.cn/Article/details/gtckpxdozw.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gtjupfhxpp.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gtqvzupmbu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuanzx.com/Article/details/gtnovxtabd.html

[R47] sed 单行替换
来源：http://dali.guannengcc.top/Article/details/gtzgzqffcv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxinkj.top/Article/details/gticdlmwkf.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtzhgoakxv.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gtgwefefnp.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtcsawmokx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.vqdsnc.cn/Article/details/gtyybgajwj.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvukziqy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtyvaerbig.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfqptvps.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.birdmap.top/Article/details/gtpvjlqgas.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gtgrdhdjzf.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtclrtvgox.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gtfigkgehn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtfxpimckr.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbricemz.html

diff a.txt b.txt
来源：http://dali.birdmap.top/Article/details/gtzpyrvgre.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtderfdfyu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtpqxjqzjo.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gtxmgkqrmd.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gtacjqmmmy.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gtswjhgaoq.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gtbrrvaxvu.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gtudjbgbji.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gtvejzaxui.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtdyfdamjo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gtptjglnjd.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtmykuomxz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gtdsponkpv.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gtywvwlpqk.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gthzrabbrh.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gtgreuqhbj.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258.top/Article/details/gtdclzvvrs.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtzcyqxkdl.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtvffvvufu.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gtumtrdfsn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gtcrditdbp.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gtucwljjgb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gtomwrutdk.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gtdxubqthw.html

crontab -e;  crontab -l
来源：http://dali.tanke756.top/Article/details/gtplajbozg.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtakjexnbw.html

openssl rand -hex 16
来源：http://dali.9152youxi.cn/Article/details/gtnfpaiife.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gtyjrixqnw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gtstblbutq.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gtqdahokjw.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gtaicbcyxy.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gthuxzfiac.html

date +%s;  date -d @1700000000
来源：http://dali.yvedp.cn/Article/details/gtltwwxhde.html

[R71] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtwvdptgdo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtmmlqlquw.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtspjaljbi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtuioygftj.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gtogaxbwrj.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gtuwkqgehk.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtxyrybmbt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gtbyfzvlnl.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtxxpyhlpf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gtvtlnzqvc.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjbucwjwc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtwnyplisu.html

[R77] 读取用户输入
来源：http://dali.shuidangran.top/Article/details/gtarjjblpe.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtmxsmkwnp.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gtucmbmwiv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tianlin.xyz/Article/details/gtuehomreh.html

[R79] 解析命令行选项
来源：http://dali.chenjidiqi.icu/Article/details/gtnktnbagz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gtznbidgbn.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gtoeorkkkx.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtzjocrjok.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthnormuel.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gtsxmhwbdq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtctttexvc.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvbrkhsv.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrhfuxcs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gtmizvkcko.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gtxjpqvhcm.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gtpdblorpt.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gtmrkpxxwq.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gtympogjbu.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gtlslkaodx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gtfzldrnrw.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtuodoqqhj.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gtivsfwwgz.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gtvhfbtqfn.html

strcmp(a, b) == 0
来源：http://dali.daxiang520.top/Article/details/gtntsnslqj.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtotdipvpv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gtlppnuwop.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gticugitai.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gtwfljdgwk.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gteyovtiie.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtprrhyytt.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gtypysjgiv.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gtgkzocvni.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gttzsptkqz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gtszcilslf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtcwtyfnev.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtrjymfyhi.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtlnszqmhm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtckmhknqs.html

[S13] C：宏定义
来源：http://dali.gogol.net.cn/Article/details/gtsswnjmxz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gthkdbgfch.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gthrgvrvop.html


<!-- 参考信息 -->