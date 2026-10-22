代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrssxaap.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cheryme.top/Article/details/gt2vbyhbhvg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.svipenyu.cn/Article/details/gt2wcalczkc.html

[Q49] 更新单行
来源：http://dali.jqgufenzy.top/Article/details/gt2uwmwrraj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gt2rkgoutny.html

[Q50] 批量更新
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcnandfa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2inhuptxo.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gt2joejtwyi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2tzuzjkij.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gt2iveujybo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujydpvgx.html

[Q53] 按条件删除
来源：http://dali.yonumen.top/Article/details/gt2xhzapkai.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gt2wwcbklwd.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gt2apgdcuik.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gt2emnkhxoq.html

[Q55] 排名（并列占位）
来源：http://dali.xylfe.cn/Article/details/gt2vbrabktr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gt2jaqnvtaj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gt2gtnptiva.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mulehvoh.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gt2pibjxuge.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2mndrzwpo.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gt2msjaquid.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2qqqjtydg.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gt2iuogoarx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vhmguspe.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gt2vedktxjn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgfzy.top/Article/details/gt2bsidcirr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2pifwcdii.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gt2dewqnvtw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2bksufpvg.html

[Q62] 分组占比
来源：http://dali.yongpay.top/Article/details/gt2rmbrftcd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2jkeiuamy.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gt2zpsjsecb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chabjmqw.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gt2ujxlcwts.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gt2cvtsweyz.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2iswxxoql.html

ROLLBACK;
来源：http://dali.aibaodan.cn/Article/details/gt2ionjqohv.html

[Q66] 行锁查询
来源：http://dali.nwbrower.top/Article/details/gt2pubrqtsz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gt2hhymiaek.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gt2rginxliy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gt2venajypk.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gt2kmsffjhl.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gt2llvliliw.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gt2dfhajxxe.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gt2zgdubhgi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gt2stknqirh.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gt2sdjikjfr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xavmikrn.html

[Q71] 查看建表语句
来源：http://dali.guowangkeji.top/Article/details/gt2dfoqgwyf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usargois.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gt2wrdywqcs.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gt2mqfickez.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gt2qgbjwtoa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gt2xhiybisr.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gt2onesvoln.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gt2qnurnxzu.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2lgkultji.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2sxlvepon.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gt2boxfhmmx.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gt2nylrqaez.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gt2bedvcfia.html

[Q77] 时间加减
来源：http://dali.gogol.net.cn/Article/details/gt2fuegpxbd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yvedp.cn/Article/details/gt2ghaalpns.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gt2gxoufgxn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aizwys.cn/Article/details/gt2hiionmtb.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gt2zuaierhh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gt2krtizymg.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gt2wicgybtu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2bojurtpa.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qucttzob.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2gqnwsvbd.html

[Q82] 字符长度与字节长度
来源：http://dali.hysaishi.cn/Article/details/gt2euxdwpzt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2ooiqbcwk.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2nlpigkhz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2ezaxdfgg.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gt2lgzwnsnk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2ztlntezp.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gt2aqvsnhwb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gt2xzknxyqf.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gt2iffchqkn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cucudq.cn/Article/details/gt2vhwecqnr.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gt2kkrhjjom.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gt2jqziuror.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gt2njaqfgop.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gt2yicallud.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2drltzcio.html

[Q89] 判断表是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfhpumnh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gt2ipdiorph.html

[Q90] 生成序号列
来源：http://dali.meibo888.top/Article/details/gt2auntnddm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gt2gmwtuzsj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2vtckytva.html

R. Bash 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmcqtbbq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2jpffhkhw.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gt2vdtctfxw.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gt2nwgvcoei.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gt2trcdebbp.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gt2anvamvol.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gt2vrafoxeb.html

[R03] 只读变量
来源：http://dali.yuxming.cn/Article/details/gt2mgsmchzu.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvsapshr.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gt2fjhfsezl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khzumhho.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gt2ycepujmn.html

name="${1:-default}"
来源：http://dali.guannengcc.top/Article/details/gt2cmgupxkd.html

[R06] 判断命令是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxxcbabt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpqykmzj.html

[R07] if 判断文件
来源：http://dali.xuanzx.com/Article/details/gt2crlmiuhn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nwbrower.top/Article/details/gt2ugwnqlfx.html

[R08] 数值比较
来源：http://dali.9152youxi.cn/Article/details/gt2otjqcjkv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gt2ltqmpzwi.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2uupbdjyf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2tulglwck.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gt2vbiuojnz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gt2zhsacdzs.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gt2mhlnbmsf.html

case "$1" in
来源：http://dali.hywenlv.cn/Article/details/gt2vqnfmqlm.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhswtran.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gt2pbmnawcd.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2bwgwrbgj.html

esac
来源：http://dali.tianlin.xyz/Article/details/gt2ibxichkx.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqifeyir.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2ofzpupxc.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gt2fjkphral.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gt2hbamlkct.html

[R14] C 风格 for
来源：http://dali.jiagoushi.top/Article/details/gt2kagqssyi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2tsppgejr.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlwahnyr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gt2trxijhky.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gt2acylhfzv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2bprmskvi.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gt2tctppiwi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gt2tjaeponu.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kctgbjqd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gt2edzhlbrg.html

[R19] 数组长度
来源：http://dali.pycfn.com/Article/details/gt2ptmkwehf.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gt2upgbhgks.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gt2kwbzvedq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dianchejie.cn/Article/details/gt2vqykybdd.html

[R21] 字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgcluxws.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gt2qlgcnfqf.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxqsndwu.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2bflqeipi.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntduhbpm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gt2xjxfbmed.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmbqcfum.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gt2dvpjgltx.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gt2uufmwugi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gt2wrdyzcwi.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmwdlpnp.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gt2tcjjykbk.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gt2yrkpkqsd.html

echo $((1 + 2 * 3))
来源：http://dali.jqgfzy.top/Article/details/gt2jaihuysr.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gt2laembdoq.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gt2fnmgyawe.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gt2skgwirvo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gt2hadmljbz.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gt2fqmwlxjd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gt2hjxxqsvr.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gt2pbyfbsuu.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gt2nbxgubtv.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptmbzqmc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gt2mtcnfewt.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gt2yrscebgq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gt2trdybimd.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gt2bhoaiorz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gt2dhvuoets.html

[R35] 后台执行并等待
来源：http://dali.daxiang520.top/Article/details/gt2yenzrelf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gt2mjujysdb.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gt2smgxdmuq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gt2owbqbsxn.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gt2nsdadiue.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gt2fighfyuk.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gt2xjrcgvnf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnalwzvy.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gntmwcpu.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2fzrdwqnw.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gt2qsywrkox.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gt2gdibpoar.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gt2bmskauee.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gt2megzblne.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gt2uxgiqtet.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2odxmpvcz.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gt2ihuhlwzs.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gt2etjywtfi.html

[R44] 按修改时间查找
来源：http://dali.iojbl.cn/Article/details/gt2zrnlinaq.html

find . -mtime -7 -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofxhfowm.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gt2djcdimbw.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzawttdl.html

[R46] 递归替换文件内容
来源：http://dali.zhongyouzk.top/Article/details/gt2aynhslvp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gt2kymcenyl.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gt2ywxsykbt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcrjrkgi.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gt2dadlmggo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tgyoabyv.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gt2ybzkjqwh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gt2nofvolxj.html

[R50] awk 求和
来源：http://dali.pycfn.com/Article/details/gt2mroytzoo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gt2mbgjtiej.html

[R51] 排序去重取前几
来源：http://dali.aibaodan.cn/Article/details/gt2nriytzns.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gt2pkbiqgke.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gt2wchzdaam.html

wc -l a.txt
来源：http://dali.ybcxt.top/Article/details/gt2gbeniomn.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gt2mqmeismk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pycfn.com/Article/details/gt2wwcjnufj.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gt2lvefeziy.html

diff a.txt b.txt
来源：http://dali.cqqwz.cn/Article/details/gt2kjsbnqyh.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gt2yzsnimtz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkuxdynf.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2fzxjlmba.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gt2azakcdya.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gt2axrchpbm.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gt2lzujhayh.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gt2fdxzddga.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gt2yywuxdgk.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2qpiahcsu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzlnzmsq.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsrlevfm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gt2tgnrqink.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gt2hkintmst.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gt2qxnqtkfb.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gt2ntfvtoko.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gt2mdoefhew.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gt2zwktltac.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gt2jowtqajs.html

[R64] 结束进程
来源：http://dali.yj202588.top/Article/details/gt2ajbdgpiu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gt2lfpdnwoe.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gt2phnudnch.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gt2rtsbznse.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nujxzffx.html

crontab -e;  crontab -l
来源：http://dali.xuanzx.com/Article/details/gt2tqoufwmn.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gt2iwpxqvgm.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gt2izmtckin.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxinasid.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2ovyagoei.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gt2crgwvsfb.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gt2dpdqohgu.html

[R70] 时间戳与互转
来源：http://dali.nanxinkj.top/Article/details/gt2bpuxndtj.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gt2meawfces.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdiqjpqo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gt2mlsajwhe.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gt2gxkxevmh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gt2osyfhsmz.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gt2gvplelwe.html

split -l 1000 big.log part_
来源：http://dali.316326.xyz/Article/details/gt2nigdeaky.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gt2sunhysny.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gt2hxkdjoop.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atiepfgz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gt2pfhthypm.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gt2igvfxhtc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gt2flytsgud.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gt2aohycigg.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gt2cgegaqie.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gt2wflsrfha.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gt2sxjpzzqg.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gt2fouucuya.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gt2nafisyyq.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gt2dwxsadtv.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gt2chntmvlj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2npvwhjzn.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gt2myysdnul.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2dntdsimj.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2hfvbxiem.html

#include <stdio.h>
来源：http://dali.cheryme.top/Article/details/gt2ktlqwkaa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbfsqzwq.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gt2hcotdxyl.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gt2lyinmgvg.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxytbppo.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gt2hxjbqibh.html

[S04] C：字符串复制
来源：http://dali.hnxiangtu.top/Article/details/gt2cpjwbfls.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2jnifizzq.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipubeizf.html

strlen(s)
来源：http://dali.nanxinkj.top/Article/details/gt2rnivjjrr.html

[S06] C：字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqapqhpg.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2aldtvvzp.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gt2yelcjutq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gt2kifnhfct.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gt2tmqazrmb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gt2hgduwqqa.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gt2imlrbocf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gt2capqewep.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gt2txrmydbp.html

int *p = &a;  *p = 5;
来源：http://dali.yanxiufei.cn/Article/details/gt2fqpngrzy.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2rpnxpddn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqfoazxe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.svipenyu.cn/Article/details/gt2feesoiuw.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gt2pterdgqx.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gt2chfmcdxq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gt2ausafgqi.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gt2wqurllul.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gt2tmfrleey.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fftcmfxs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoqdvvt.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gt2jslligrv.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gt2aobascgl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lmylavqz.html

x |= (1 << 3);
来源：http://dali.hammf.cn/Article/details/gt2aikjggqq.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2lbkxngkg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmbavrqf.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2rfhzqvgj.html


<!-- 参考信息 -->