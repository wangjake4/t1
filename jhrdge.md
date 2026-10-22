代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.guowangkeji.top/Article/details/gt2zipuokkw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gt2tccizhdb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gt2irtmhvda.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gt2lqhumanc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blttizzl.html

[Q50] 批量更新
来源：http://dali.havefunace.top/Article/details/gt2urppawpg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gt2oeehjvln.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gt2fnrpqsov.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2agpagwlg.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gt2fdbzqfbm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2sxdezmtx.html

[Q53] 按条件删除
来源：http://dali.daria6918.cn/Article/details/gt2ajioselv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gt2wlhpjicd.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gt2mmpkdaub.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gt2rojcmzfm.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gt2zvpkpool.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gt2sqrlheyg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhoulong.xyz/Article/details/gt2wolinklv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gt2utgkefto.html

[Q57] 行号
来源：http://dali.meibo888.top/Article/details/gt2lejnduxj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yongpay.top/Article/details/gt2uujpsozd.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gt2epzjszzo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2jkuyndoi.html

[Q59] 分组内累计
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxqohlmw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2xejrwauf.html

[Q60] 取上一行 / 下一行
来源：http://dali.guannengcc.top/Article/details/gt2affvduzl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jianghu66.top/Article/details/gt2mjnvtfru.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2ltfulpzb.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrruvfzy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbbdftts.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gt2fijtyjnd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2skanfbwl.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gt2onimsxri.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yueranfly.top/Article/details/gt2yjpfbclj.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gt2rndloyvi.html

COMMIT;
来源：http://dali.aibaodan.cn/Article/details/gt2fqcmyppc.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gt2muwtaikr.html

ROLLBACK;
来源：http://dali.xylfe.cn/Article/details/gt2tefctrbu.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gt2wjphnpqh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gt2csabewvg.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gt2zjazhyia.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gt2wylfhvmh.html

[Q68] 保存点
来源：http://dali.nanxuanxn.top/Article/details/gt2awplnrre.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gt2cscxfnyw.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gt2vlvvvfdw.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gt2mcnuymdf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gt2dwfbmmrc.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gt2wacwyxcf.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gt2ueqcokst.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gt2faohzeha.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gotoacloud.top/Article/details/gt2tbkuzcaa.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2cggtorzj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhvkbet.html

[Q73] 查看表状态
来源：http://dali.sweek.top/Article/details/gt2dbtgzgfe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptdltthv.html

[Q74] 强制使用索引
来源：http://dali.nanxuanxn.top/Article/details/gt2xgmkmhsx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jianghu66.top/Article/details/gt2eezyhoof.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gt2ugxsyqxy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2yrcsrqlc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zgcwwprc.html

[Q76] 按天统计
来源：http://dali.iojbl.cn/Article/details/gt2ksycfslq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gt2zazzygdz.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gt2dwhovook.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gt2patfdvcb.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gt2fpfebvzv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gt2flwcsmue.html

[Q79] 字符串拼接
来源：http://dali.jianghu66.top/Article/details/gt2vjujbxxb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gt2rvavdmnx.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gt2mgzfzzss.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jptttggd.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gt2llmukwes.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxxkxluk.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gt2dyumryzc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2acgurqud.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2inqrqmbi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2rrlqzzig.html

[Q84] 去除首尾空格
来源：http://dali.snrcjt.cn/Article/details/gt2ymhvmzvm.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2cvotjilk.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gt2hpjbexbw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gt2uirfaguh.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gt2gdjglttc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gt2ricmqqel.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gt2gnkhbiel.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gt2jhjcneqv.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gt2npntswga.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gt2gyutkxap.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2zoltjhev.html

[Q89] 判断表是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsmsiavm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xziqi.cn/Article/details/gt2qgaonmbl.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gt2supqobio.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gt2qnbjedij.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2bomeojxr.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gt2ejmyfywy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2fxivrena.html

[R01] shebang 与严格模式
来源：http://dali.zhixingplan.top/Article/details/gt2ftlopqlr.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gt2wttkamol.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgszfeag.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gt2zgyucgwz.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gt2cciebvyw.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gt2jjhxdvvx.html

readonly PI=3.14
来源：http://dali.yj20258888.top/Article/details/gt2tiqkqzle.html

[R04] 位置参数
来源：http://dali.cqqwz.cn/Article/details/gt2tydtbjnq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gogol.net.cn/Article/details/gt2mzecvsio.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gt2femmxolo.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gt2chgdalfo.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gt2iomqflqz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gt2wqgcvplq.html

[R07] if 判断文件
来源：http://dali.gzhubu.top/Article/details/gt2ibogcczt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmuyfbdc.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gt2trdjnjqo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2uvcbbcwj.html

[R09] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gt2cfuzlykc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gt2vtsivpgk.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gt2vygkiayu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gt2lyqkruiq.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gt2jcoxhzbw.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gt2fmjmlnot.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2ftcksmaq.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gt2qnaldllc.html

*)     echo "未知命令" ;;
来源：http://dali.jianghu66.top/Article/details/gt2jdmjrbcp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2oezkzbxm.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gt2vgccabns.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gt2ipsseyuw.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gt2skjujihh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gt2xeyokqgm.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gt2azeoboik.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2sbogjkxj.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2rlnwfjrt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gt2itgruyoj.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gt2tinamsbt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgqzhyxb.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gt2cupbtaxr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gt2nwqqlhlb.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gt2vhwtxvri.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gt2gpyfbzqj.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2gqyoauxs.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gt2zewxdhil.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gt2wafhctzh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gt2llcdjhmd.html

[R21] 字符串长度
来源：http://dali.cdnleiting.top/Article/details/gt2mymfxtla.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gt2rdhthexg.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2dqmffkom.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqyfjqzg.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gt2ysqodlep.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gt2ivetjwui.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2nhyusiph.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gt2bppzhujk.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gt2wnenbwpa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2iswbkopk.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcpuhopg.html

now=$(date +%F); echo "$now"
来源：http://dali.dashuyun.cn/Article/details/gt2pxwauvfx.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gt2egxacntx.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gt2gwpfgqrq.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gt2vpuxidac.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gt2nafjwapu.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmdfhsao.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbtywtrf.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2esczzwtt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gt2kvtpzfef.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gt2mwvztbmq.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yckjbhbb.html

[R32] 参数个数校验
来源：http://dali.xziqi.cn/Article/details/gt2ihbybehp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2impkcilg.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gt2hctktpdv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gt2ihwanphj.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gt2hegtmoru.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gt2ntcgwnxj.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkwpfopm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gt2yudicaog.html

[R36] 并发执行多个任务
来源：http://dali.yangfankeji.com/Article/details/gt2gmkpnren.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gt2szvunptk.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gt2vsfqrhzw.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gt2kdwvyzmy.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gt2tbbqphrg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cucudq.cn/Article/details/gt2lzefuvjn.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gt2pjjuormj.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gt2kopbatxj.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2yrraldpn.html

echo "log" >> out.log
来源：http://dali.guowangkeji.top/Article/details/gt2qkdhraqt.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gt2vmsefbkd.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258888.top/Article/details/gt2nbxhetxu.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gt2ywsumfic.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twcrnfru.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gt2uwvtrnmb.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gt2fczvunuy.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gt2gpnnmfyl.html

find . -mtime -7 -type f
来源：http://dali.gotoacloud.top/Article/details/gt2xgfhapnl.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gt2zeaksdro.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gt2vkadcoag.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gt2jjcwoeon.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gt2snognzmr.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gt2sgvmxlje.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2eqnztnph.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gt2gvtjvckh.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gt2dxsvyksk.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gt2rljxskvk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gt2gqvylcbn.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gt2ifsvewhg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2gbncigte.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gt2qahlqyak.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gt2vbbrmqiy.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gt2xbbfidwb.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gt2xtxsbadh.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gt2atcelquo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gt2aqbdrnty.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nctjumcx.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gt2aolyiuat.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gt2spchvhea.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gt2nkothyjn.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gt2hzcpqrqy.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gt2fmpgkzue.html

[R57] 远程执行命令
来源：http://dali.guannengcc.top/Article/details/gt2pxefybsf.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gt2rzdzytwr.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gt2cyvuomcg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gt2ljbywxar.html

[R59] 发 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gt2dshdkxdx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gt2tgovrwpb.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gt2gvriozhr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gt2hpvzhzhq.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gt2bsgmgyzm.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gt2opfpditl.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gt2omxpkuht.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnwnviva.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gt2tfrwksxs.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndkasili.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gt2btxlqcvt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.9152youxi.cn/Article/details/gt2lrhbsdnd.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gt2bcddcnyf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gt2mgvepkam.html

[R66] 定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvxwwuuw.html

crontab -e;  crontab -l
来源：http://dali.sufxvd.cn/Article/details/gt2luveewzi.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gt2axpqxzqe.html

openssl rand -hex 16
来源：http://dali.yuanzhike.top/Article/details/gt2migwkvtd.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gt2ahzclamv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gt2kfqjpomm.html

[R69] 生成随机密码
来源：http://dali.sxryk.cn/Article/details/gt2sndbuxhx.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gt2qqgbsguq.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gt2tphejesy.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gt2rcjhowhz.html

[R71] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gt2ypgzjkvk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gt2bhgjjvjy.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gt2rcsdgwit.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2objyypxz.html

[R73] 分割大日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kawuauly.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbuggusp.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gt2emuqskff.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ydzc1.top/Article/details/gt2nfrgbtiq.html

[R75] 导出环境变量
来源：http://dali.cqqwz.cn/Article/details/gt2gngtfxit.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfwhaxqu.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gt2dwyqumix.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gt2jppqwzks.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gt2ntzzkuic.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gt2ivcmtlzk.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhzsxsxu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xylfe.cn/Article/details/gt2wwnrgrzb.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gt2vhdpshxd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evogzeal.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gt2sdfrxbhh.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gt2jxbxuewf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzhekiyr.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gt2jytgptup.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2iylczudx.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2xswmwwhs.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gt2qjvyvqhg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gt2ecnqcxkp.html

[S02] C：变量与格式化输出
来源：http://dali.sufxvd.cn/Article/details/gt2lbonreld.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gt2zkyewvjq.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gt2cmgwzvxe.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gt2xenftgkg.html

[S04] C：字符串复制
来源：http://dali.fengsongda.top/Article/details/gt2irvynpgs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gt2cgozwrln.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gt2pbgkjmnq.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gt2tixrsxoq.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2iwoahjzo.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekoxajkc.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gt2jdhwpbob.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gt2nmraonvo.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gt2kiqvlrih.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpwcggja.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggtzjtoy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gt2sewhojbn.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avmvhkqw.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gt2gqhtpads.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2vxajpbjz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gt2zvnrihaz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckmckccf.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gt2cpgodprx.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izevzsii.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gt2oqlwfopz.html

[S13] C：宏定义
来源：http://dali.tian-w.cn/Article/details/gt2wztwfqeg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqnvttuc.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2vncmdwnt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpqtdmxe.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gt2xluewcnw.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gt2ixhnzppe.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxmhmmrb.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gt2hyzpzdii.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gt2zubrhqeb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fenpkhnd.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gt2icvmpnjj.html


<!-- 参考信息 -->