代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gttdkntbnj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jlsjyb.cn/Article/details/gtlpztmddd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yangfankeji.com/Article/details/gthcozbpvt.html

[Q49] 更新单行
来源：http://dali.xuanzx.com/Article/details/gtbjeaimey.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtbggglxxc.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gtjcqlkckg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gzhubu.top/Article/details/gtbevffuiz.html

[Q51] 用子查询更新
来源：http://dali.shangyingyoupin.top/Article/details/gtntgbfsxy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.9152youxi.cn/Article/details/gtuthvzvgg.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtqwpdkyfg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtssjmhwtk.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gtdnoniuev.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtconnjgvx.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gtvqqpyfgt.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gtdifhbdoo.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gtmisigxef.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtboknybdm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gttgrcnjkj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtnlqaafas.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gtbdkvpqxw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtcciztrnf.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gtgstoviji.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtrqhkpkyl.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gtovuhlzcy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtzsxcaspe.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj202588.top/Article/details/gtzvmchqlf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gtabndbgis.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtwfmwrwnk.html

[Q61] 移动平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gthajlnwrc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtsvlnwcts.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gtoohqggzo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyxupqsa.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gtuvpnquke.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gtnijawzsv.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxcnwzje.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gtbmlfbvbf.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gtlklcwzst.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gthnrntmkn.html

[Q66] 行锁查询
来源：http://dali.yvedp.cn/Article/details/gtzrhvyqai.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gtcwpllnaf.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gtgmtrdhkc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gtjswhjhwa.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtdkcikpko.html

SAVEPOINT sp1;
来源：http://dali.gotoacloud.top/Article/details/gtaafgktwb.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnxodqva.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gtjrpdtxvb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gtylsxfwrt.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtabnerehf.html

ANALYZE TABLE users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwljzhgdg.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gtxvugehte.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gtlzfkfnus.html

[Q72] 查看索引
来源：http://dali.feifeiyinyue.top/Article/details/gtstzkfexl.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtmmyplvuc.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtyqqxrjtl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gticdxhtxg.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gtcjmzyosy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gtxdkrinax.html

[Q75] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmfsyway.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtbttqwkly.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtnmdhkllh.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtjerynzmp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gtsafrlluf.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gteritvwuy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gteovcnddw.html

[Q78] 当前时间
来源：http://dali.jiagoushi.top/Article/details/gtakbabefc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gtvdgxaojf.html

[Q79] 字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtmknhxkkw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sweek.top/Article/details/gtwilotvym.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gtuhyxgvcx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtigejtksq.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtjgjfokvj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtdauesmzn.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gtewpwvotx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtfghnusxi.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtuuyzttwr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtumxsuyet.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gtttyggqam.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcreeddrm.html

[Q85] 数值取整
来源：http://dali.hfpthk.cn/Article/details/gtbxgogicb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gtdmgkihwk.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuymqlqkf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gtoryqjgtp.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gtmzhfhgmw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnqzz.top/Article/details/gtwqyrwosh.html

[Q88] 行转列（条件聚合）
来源：http://dali.xylfe.cn/Article/details/gtnpfixpdl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gtpkhlesbl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtvymlcdru.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gtklxczmau.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gtbdoucqlt.html

[Q90] 生成序号列
来源：http://dali.hammf.cn/Article/details/gtgmcvsupz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gtxjxpghgl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcvygndjb.html

R. Bash 专题
来源：http://dali.gzhubu.top/Article/details/gtjeafzjeo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gttronzeay.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gtqsggnvuz.html

#!/usr/bin/env bash
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbqpsfac.html

set -euo pipefail
来源：http://dali.shanyushiyangtech.top/Article/details/gtragrkyta.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisgkpxlz.html

name="Tom"; echo "$name"
来源：http://dali.xinyue.icu/Article/details/gtsvnvkmiz.html

[R03] 只读变量
来源：http://dali.xylfe.cn/Article/details/gtkurpmoww.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gttpifsacm.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gtnkzcyguq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtgfhpxvko.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gtykycyibd.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtvziufnui.html

[R06] 判断命令是否存在
来源：http://dali.sxryk.cn/Article/details/gtrzwjrmwh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtrwqamrfg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gtbksymeux.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gtcmmgqzyu.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gtumzkklqr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtsflnphil.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtkjlzpcky.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gtykzapmhn.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtpusobcxy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtnwpxbhik.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gtvirjvdku.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gtirepqdfl.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtqbhpjkvy.html

stop)  echo "停止" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtkztrqtvr.html

*)     echo "未知命令" ;;
来源：http://dali.xinyue.icu/Article/details/gtaonjxjoh.html

esac
来源：http://dali.hywenlv.cn/Article/details/gtvyewuulu.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtlpvcvdkt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gtwaukqzen.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gthnrtbuyq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtdysneumn.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gtmqmkpgnc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtupetwfcs.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtfglobqww.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gtuoinaxrh.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gteizhbkfi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtomehitsg.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gtvsuecypy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yongpay.top/Article/details/gtkrrytxce.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcpjomkv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalerwnla.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtgbagjate.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gtmfbapzfm.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtdgxlewnb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaaztvhq.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gtgalutrbt.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtvnmasumo.html

[R22] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtoswshtto.html

echo "${s:0:5}"
来源：http://dali.hammf.cn/Article/details/gtjwkrsgig.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtzkgajvfq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daria6918.cn/Article/details/gtdsnttmld.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtumxblvcf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gttfbgtqbx.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gtmlogsxvl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtzudxzhww.html

[R26] 命令替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkmcnuwm.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmoietxz.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gteuncyiix.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gtcnmrufze.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gtyjikbzyt.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gtcivflfxq.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtztmdzzyg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gtycdfvlyo.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeollfhu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtkrvrzzvs.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtsbihyzbg.html

f() { local x=1; echo "$x"; }
来源：http://dali.shzxlz.cn/Article/details/gtakaaonoc.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gtowwvuakr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtoxsnajnr.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gthfnyswpe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gtopgyzcim.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gtettwwstm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtqvfoedsx.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gtupoezsjx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gtyqbbmlax.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gtxxfegvha.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gtyyutvdsx.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gtefgwotuy.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gtphmmzbti.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gtosrpsitp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtnahsyouy.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gtgagnqkls.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gtlwionzly.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtfkugrznb.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gtilsetuvu.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gttotlcsis.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtklynbgjh.html

[R42] 输入重定向
来源：http://dali.jqgfzy.top/Article/details/gtqkisbyfd.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtqugaoqkr.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbybmxyy.html

find . -name "*.log" -type f
来源：http://dali.zdqjudy.top/Article/details/gtogjhljia.html

[R44] 按修改时间查找
来源：http://dali.fengsongda.top/Article/details/gtontaftxn.html

find . -mtime -7 -type f
来源：http://dali.yongpay.top/Article/details/gtgatgtver.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gtokckehro.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gthfxbeyrt.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvewxxzo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gtxosnbwgz.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gtdrunsezw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtwuafgyym.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gtjvdqqima.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtfdoedarb.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gtzcbewahu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gtyeedlfpw.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtxilkrqcn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtwzkmbgha.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlflqbgo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gtobyfxttx.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtwahbbjql.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtzvibrrul.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gtmbjrmjph.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gtlmrhpmls.html

[R54] 比较两个文件
来源：http://dali.sysykeji.top/Article/details/gthzbgahkh.html

diff a.txt b.txt
来源：http://dali.quarkkingdee.top/Article/details/gtmbzoroyj.html

[R55] 压缩与解压
来源：http://dali.guannengcc.top/Article/details/gtawiucmsi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gtmmkeljtx.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtbrkynefo.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqoeaaot.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtglaazkhn.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gtuzpawrdi.html

[R58] 下载文件
来源：http://dali.smart0.xyz/Article/details/gtgfcbvgxj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hysaishi.cn/Article/details/gtcikupfmi.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gtklcjhzno.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gthcnyeknf.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtdmnwvsvo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gtyarxplym.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtobenkkpx.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gtcuxyjwrj.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtitbqtizj.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gtathgjzxg.html

[R63] 内存与进程
来源：http://dali.meibo888.top/Article/details/gtlrebhvhi.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gtlghcmths.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gtotruildf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gtzgvdkany.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtsmxrvcad.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gtptrojkqa.html

[R66] 定时任务
来源：http://dali.0kj1m.cn/Article/details/gtwepzkbmf.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsededtg.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gtffihrqsj.html

openssl rand -hex 16
来源：http://dali.hongshengwenyu.top/Article/details/gtikgrrqhj.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gttvxqwtgy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtnaznugzg.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gtvrlnjwpj.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtknktbbyu.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gtmszvxlju.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gtweziujmz.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtvqrfvgzc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtgtqtnapy.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gtlfowdkrm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtjbxzzkjz.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtqxjsiprx.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtgjjaxkxx.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gtklnihzfl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtcfackgre.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gtgudcamgd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndjjkxgw.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gtkxqdoawr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtffdtlqmp.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtaulqiyim.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangtech.top/Article/details/gthjzsryve.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtvqvhzgcy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gtzdsaidsg.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gtyazmzuhl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtkgxivlmn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gtyqqloinu.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtxvtsyoyr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbtvixotw.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gtsrajkyro.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthrdfxwjy.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gtitmjyjlr.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gtoiswbjvh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsyppoqbj.html

[S02] C：变量与格式化输出
来源：http://dali.daxiang520.top/Article/details/gtihozrmul.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtikojidyl.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gtbpuhtsbq.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gtfjbzwohi.html

[S04] C：字符串复制
来源：http://dali.sweek.top/Article/details/gthyeabnrk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gtplnnyubd.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gtugdxbbtn.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gtfsetspzg.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gtlvdlfdtn.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gtzhickfen.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gtenjozoao.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtawbcqgmv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpdabzos.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtbiekhanz.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gtuuqraknn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gtqxzacljt.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gtwxkipzye.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gthjcepidz.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtzmomozrg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gtdusvfrtb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gtebodptfo.html

fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtdrhagfrs.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtyunoyluh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtkwcuqsfx.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gtptfaxdkv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gtiwudlurc.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtrrzjkirq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gtkufezmdu.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcptsnnm.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtiregzwqx.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtmbvaqzom.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gtkhlrttyz.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtecwiuebn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gtdqzxquqx.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtgzsribna.html


<!-- 参考信息 -->