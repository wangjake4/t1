代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gt2hatwjgyb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gt2iloxbgoi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gt2gstwbqhz.html

[Q49] 更新单行
来源：http://dali.chenjidiqi.icu/Article/details/gt2bntftkfp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gt2irqlqkuf.html

[Q50] 批量更新
来源：http://dali.svipenyu.cn/Article/details/gt2sneeehgw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gt2hzbxtdee.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gt2ojamiiek.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gt2wnvjezqu.html

[Q52] 删除指定行
来源：http://dali.pengpengdd.cyou/Article/details/gt2wekhyzpu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2byavfmtq.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gt2pmtrgzqb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gt2qicjxpzp.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gt2jeqtxldo.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gt2qbxwfspc.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxekfpxf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gt2xfkgzmiu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gt2enufdesh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gt2zzaiweqp.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dowauhul.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2afttkuzb.html

[Q58] 累计求和
来源：http://dali.hfpthk.cn/Article/details/gt2wvttscru.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2drhedxum.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gt2yadgtzrp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2jymiettx.html

[Q60] 取上一行 / 下一行
来源：http://dali.cqqwz.cn/Article/details/gt2kazdfoeg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gt2qylqmajq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2ophjmdvn.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gt2dgvkorlq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2zyneupri.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gt2zwaxrhsq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2vryjohef.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2vywegisp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gt2wmyxbyyv.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gt2amnyvdme.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2iebzuwqx.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gt2deyjqybi.html

ROLLBACK;
来源：http://dali.redwolf501.top/Article/details/gt2zvatohhb.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gt2zjzcfnwe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gt2kxgxfjcm.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gt2lenjndxk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tanke756.top/Article/details/gt2ibvywbpq.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gt2yotjmioi.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gt2otwpeymr.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gt2oyxegpmf.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gt2ibtwqzxa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guannengcc.top/Article/details/gt2nqmqydti.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gt2vkcjifjh.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gt2xudkdctt.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gt2knlsflkk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xeawbksy.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gt2duwlugkk.html

SHOW INDEX FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2oykdessm.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gt2xxnzkjnk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gt2auxmweiz.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gt2kppdplpn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gt2swswtpic.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gt2gpsfoxwu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2ndgxkuoa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daria6918.cn/Article/details/gt2jdhpvzmc.html

[Q76] 按天统计
来源：http://dali.ehwqpu.com/Article/details/gt2vzwvaymk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gt2iyqsulyn.html

[Q77] 时间加减
来源：http://dali.gotoacloud.top/Article/details/gt2qjnqmyzl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gt2sivgfxcg.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkfbvgxu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlybtknc.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gt2ktecuuxn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gt2kfnqlgvh.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gt2mnscbnok.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2msvnajjg.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2feldcrse.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2igphyicy.html

[Q82] 字符长度与字节长度
来源：http://dali.chenlongwang.top/Article/details/gt2jglbdaah.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2gyybxkvd.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gt2vphkxviq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2korebtmm.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gt2caesbyeg.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2qujjlfty.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gt2dfssatoz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yonumen.top/Article/details/gt2qwnktmim.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gt2oabrudkv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shuidangran.top/Article/details/gt2hhgqvtki.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gt2xjnopput.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gt2kulbbehw.html

[Q88] 行转列（条件聚合）
来源：http://dali.svipenyu.cn/Article/details/gt2ytimefhl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gt2pveusxwb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2cgeekvyd.html

[Q89] 判断表是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2aoicdako.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gt2zetubawq.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqcnfhzd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gt2iwvgmsbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojctylmh.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hbxuagpf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2kiwoaaxq.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gt2mdsujovr.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gt2yylmsnvh.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gt2pabecrom.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gt2cmkvuwdc.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gt2thhhjqqv.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gt2dvbvyvoi.html

readonly PI=3.14
来源：http://dali.dianchejie.cn/Article/details/gt2uxdhxxpo.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gt2ngwbaeyh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gt2gorjmafw.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gt2tgarubpj.html

name="${1:-default}"
来源：http://dali.sysykeji.top/Article/details/gt2xozuuzgw.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gt2tsdsfwpx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gt2efuqakdd.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gt2ldulcztz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2dwwzrwuk.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gt2jzggstrs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gt2lposagcb.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gt2sukfhead.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2vkhztici.html

[R10] 正则匹配
来源：http://dali.shuidangran.top/Article/details/gt2vueahort.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gt2tbobkhdt.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gt2qogbypsr.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbziqaeb.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gt2covpaqek.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gt2zfqirstf.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gt2ifkyvwzo.html

esac
来源：http://dali.yj20258.top/Article/details/gt2oghubjio.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gt2elvkrpdf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gt2szzjagzq.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gt2jmuoiyys.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gt2yvfucfrm.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gt2xeugtiix.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gt2nnkqufvx.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2sapjsxea.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gt2nvphfqxr.html

[R16] until 等待条件
来源：http://dali.meibo888.top/Article/details/gt2oweubqqy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfikxwpr.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gt2jpgrmzfb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gt2wyoyajlb.html

[R18] 遍历数组
来源：http://dali.cucudq.cn/Article/details/gt2maqrfctc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gt2prpwcfqi.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gt2ovoxxjzn.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gt2yeqdnnpr.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gt2jpsywtkw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aizwys.cn/Article/details/gt2qyicgqzt.html

[R21] 字符串长度
来源：http://dali.cdnleiting.top/Article/details/gt2broqtvsq.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gt2yhsrmgsk.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2vxgaryou.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gt2cbbfoqbi.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gt2uiuftoab.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2keyvjdjw.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2mweeusot.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gt2kemquwla.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agtqnpxa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gt2tspfsgtc.html

[R26] 命令替换
来源：http://dali.chenzaomai.com/Article/details/gt2rxjlnmap.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gt2qxxbktox.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbvxoiok.html

echo $((1 + 2 * 3))
来源：http://dali.sysykeji.top/Article/details/gt2butcffwp.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gt2vgyeqrqh.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxalbyjl.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gt2dlailrbw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gt2remrngoy.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gt2zsasjuwr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gt2txkftzki.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2exkuspun.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gt2rakcaqvl.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opdrgjeq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gt2ipouoxon.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gt2pwqsfkhn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gt2zwxqbhin.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gt2asrfpvsf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gt2qteitski.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gt2hbpuuodo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gt2llqupzvp.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gt2zfrfjubz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gt2rqqcdfio.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pczfbsoa.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gt2ynyeqcrj.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gt2juwasxuh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gt2ailfmwul.html

[R39] 重定向标准输出与错误
来源：http://dali.316326.xyz/Article/details/gt2kndaiubg.html

cmd > out.log 2>&1
来源：http://dali.cucudq.cn/Article/details/gt2rswbklds.html

[R40] 追加写日志
来源：http://dali.gogol.net.cn/Article/details/gt2npcnqalz.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gt2gjqlyzhq.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gt2jealkdca.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gt2enhebfhg.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gt2buhzoara.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gt2stjfsczd.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gt2llmjjciu.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gt2vhnygdty.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gt2fskappwp.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gt2gbyncdaj.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gt2cqffyvdl.html

find . -name "*.tmp" -delete
来源：http://dali.cdnleiting.top/Article/details/gt2evtftfqf.html

[R46] 递归替换文件内容
来源：http://dali.svipenyu.cn/Article/details/gt2roizhxmq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gt2vbqaaoum.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gt2xjrpcvfk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2vedbpnrh.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gt2ciyanqtt.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2ujqogzuz.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gt2dbwstgom.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gt2gainrphh.html

[R50] awk 求和
来源：http://dali.cheryme.top/Article/details/gt2awezcyhw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2cesfjezm.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gt2apilryjt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gt2zyrdyxgf.html

[R52] 统计行数
来源：http://dali.gotoacloud.top/Article/details/gt2egktdppo.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2lyglbocj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fiubilgw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gt2yjqhsklu.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ysywebhz.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gt2gsjqotjg.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gt2mvdagomy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.kuanghao11.cn/Article/details/gt2nnjrdrxq.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gt2oamsdqse.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gt2fpamsykg.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gt2gyugmbkh.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gt2vbshtwxw.html

[R58] 下载文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ohrwauhp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aibaodan.cn/Article/details/gt2fbumxauj.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2lrpvntdo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2azjqhsot.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gt2erljpmnm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gt2wbarzguc.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gt2hhdaetza.html

df -h;  du -sh *
来源：http://dali.yj20258888.top/Article/details/gt2cxowaukq.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gt2csdmeilp.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gt2opdggtqw.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gt2sqvzvopt.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gt2keowpkmb.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gt2mesbmlch.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gt2neazkfru.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gt2zyztdwjm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gt2xwtzhazi.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajzgqmzu.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gt2ztxhqqct.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gt2xsdkhbiy.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gt2dfpyezcj.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gt2xdnehfkf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpnbsfaq.html

[R69] 生成随机密码
来源：http://dali.meibo888.top/Article/details/gt2lsdddvqf.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gt2qtsbxdiz.html

[R70] 时间戳与互转
来源：http://dali.nanxuanxn.top/Article/details/gt2mnkrqpzn.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gt2mxhgmzvu.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbuajads.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gt2vfbpkdqo.html

[R72] 等待端口就绪
来源：http://dali.ehwqpu.com/Article/details/gt2strvxyph.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gt2uwdbleet.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gt2dyqflaeo.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gt2ubzmjcyc.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gt2bphjwvfl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gt2hsymemhy.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gt2zyboxswb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gt2apzyricm.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2xeoitvnj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gt2mfiqfxbs.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gt2kpkgqait.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gt2iyysgpcd.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gt2eoklblxn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gt2mwiboajf.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2pthslfku.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gt2glmatwjn.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gt2htjrvlrl.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gt2utbrgezh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2adfohfdg.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gt2icnoihmj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2qevrakaq.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gt2ruvsddgf.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gt2bszcabue.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hjdtejqy.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gt2idpfaynn.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gt2rpobaxku.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gt2vmfwzoic.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gt2okrvjpcg.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gt2csrlbpbg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2isvobdum.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2ffjqhpvl.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gt2nfbzeyxl.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gt2etpmihpz.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gt2utjkhpkm.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gt2xnowecon.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gt2lgrpfujh.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahehbogs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cplrvlsk.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gt2imrxmzng.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkuqzzob.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gt2eqevwxtp.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uawmlnfx.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2zgfkezpx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gt2crylkpcc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gt2lumybcfi.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gt2hziaxtpx.html

[S12] C：写文件
来源：http://dali.fengsongda.top/Article/details/gt2wviihnkj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gt2mtrspiay.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gt2wuhnqftz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gt2tqwlrjgz.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gt2klgysxmq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gt2huerlnso.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gt2xxjudqho.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gt2tjtrwakx.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gt2yomrevba.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gt2hgvethsg.html

[S17] C：安全拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gt2unyixsls.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gt2wwichtuf.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2fgrbyyhs.html


<!-- 参考信息 -->