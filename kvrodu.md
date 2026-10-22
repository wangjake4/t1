代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gt2ajpdjfnt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhixingplan.top/Article/details/gt2khwgkbmt.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gt2plqonqcx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gt2lrkncopm.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hacrlwia.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcqglwwe.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gt2kjqlxpja.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gt2hkxpebud.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2iiqxobqh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcjtbfgu.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gt2vwyozeks.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gt2lboesohu.html

[Q48] CTE 公用表表达式
来源：http://dali.xziqi.cn/Article/details/gt2mkfmqajv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gt2jgbtkppp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gt2ohhfpkqj.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gt2klygexza.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gt2fzjrndft.html

[Q50] 批量更新
来源：http://dali.tianlin.xyz/Article/details/gt2pbxgaypf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gt2mmoowues.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gt2ircwkjsi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2mbkugkmi.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gt2ampccpzf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2byxlndfu.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gt2auauocgk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gt2kwnfbfhp.html

[Q54] 清空表
来源：http://dali.aibaodan.cn/Article/details/gt2oezzosng.html

TRUNCATE TABLE logs;
来源：http://dali.zhengqikj.top/Article/details/gt2rvjvssou.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gt2bebwgpvh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gt2pwybzmze.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gt2qyvzmuro.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gt2hlieoxcy.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gt2yprtrwws.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gt2srozrynz.html

[Q58] 累计求和
来源：http://dali.nanxinkj.top/Article/details/gt2fpahdjty.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2smfegmrw.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gt2dkthsams.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2shuspwvx.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gt2wolmzgtt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gt2rgwnstsj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjrpxdur.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gt2kxujyyrp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2jtejlyfz.html

[Q62] 分组占比
来源：http://dali.shzxlz.cn/Article/details/gt2aakvtgqy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2vhppuaci.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gt2myobrabj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gt2vappwqti.html

[Q64] 提交事务
来源：http://dali.hywenlv.cn/Article/details/gt2qzbehymp.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gt2icrslfgb.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gt2tothhxja.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gt2mbaifkpj.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gt2hebebpev.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gt2fpvubnvx.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gt2zzwhaoyb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gt2cwnfewkj.html

[Q68] 保存点
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpyeqsng.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gt2uqdglltc.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gt2binbokzj.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gt2ddecqjqk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gt2feaqpdwe.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gt2hpaoxfui.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gt2chuxrodl.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gt2wlxufinl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gt2mhvpyzsc.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjtfqpsw.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2zvarkhtu.html

[Q73] 查看表状态
来源：http://dali.nanxinkj.top/Article/details/gt2yfjjeokv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gt2sruwlapj.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gt2xixewslw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aizwys.cn/Article/details/gt2zsqshpjj.html

[Q75] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2cootmatu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2bkqcayxx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gt2fqgmvpsd.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gt2xsyoqhqj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenlongwang.top/Article/details/gt2ptxcgyim.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gt2xgagsaec.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oosspqzr.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gt2qvvaklfv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybtvzqsl.html

[Q79] 字符串拼接
来源：http://dali.sxryk.cn/Article/details/gt2hbihbrbx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gt2ojvezzet.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gt2vwziffcv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2counpdcp.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gt2xgsbkkde.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2ofpchvsl.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gt2yvxwogfx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2zrdjwwql.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gt2aivmdico.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2cbxyccgx.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gt2jekkvtvr.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2kiocvgum.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gt2uzuxtwro.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.andypj.xyz/Article/details/gt2qbsfqjnu.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncpoqzdk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gt2rkjlsbly.html

[Q87] JSON 字段做条件
来源：http://dali.kuanghao11.cn/Article/details/gt2koabzauo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gt2oqenvsov.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gt2aaudaixy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gt2wwmeyqxm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2swkhysek.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gt2xezhggoq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnxiangtu.top/Article/details/gt2zkfclpfx.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gt2hbitepot.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gt2alhdcevd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ensbapyb.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gt2tqyzbkyy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2nrlassdk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dopisfvl.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gt2medxulpu.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gt2jzdlovww.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gt2ttqqgfeq.html

name="Tom"; echo "$name"
来源：http://dali.yvedp.cn/Article/details/gt2zkdplrox.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhsdpppk.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gt2minenroj.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gt2fhxtxrsp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jycnvwaq.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gt2yqweoiha.html

name="${1:-default}"
来源：http://dali.hammf.cn/Article/details/gt2stgqvrhu.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2hkkfdlhq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sweek.top/Article/details/gt2nibblwyz.html

[R07] if 判断文件
来源：http://dali.jiagoushi.top/Article/details/gt2njboceuo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2xqsrtpcj.html

[R08] 数值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgrhsroe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2nioswazn.html

[R09] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gt2rilonxoz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gt2jpvrchfe.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gt2mszcnxus.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gt2ktuzmvkp.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gt2ubsohqkh.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gt2omrvpswz.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2yxybfxbc.html

stop)  echo "停止" ;;
来源：http://dali.sweek.top/Article/details/gt2cjicaieh.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gt2outitwax.html

esac
来源：http://dali.hongshengwenyu.top/Article/details/gt2qautyvzf.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gt2udcphkwz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zbrqnouz.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gt2ryuadwar.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2putjcvpr.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gt2hisuxhda.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gt2mogjsanh.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2okjneloj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gt2trcjrtih.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gt2ejxaodlm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2ebrlgyns.html

[R17] 数组定义与取值
来源：http://dali.birdmap.top/Article/details/gt2gfrowcbb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gt2hpukmqza.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gt2ceimfmtu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gt2pojgnhvd.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gt2kwqclmfq.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gt2hjemdxgu.html

[R20] 关联数组（字典）
来源：http://dali.haohaochexian.top/Article/details/gt2xhawgwuv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gt2dlytswzi.html

[R21] 字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2nqznxeqp.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gt2rqttrfad.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gt2fuxssvla.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gt2jlhwdrif.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gt2nlepwrhw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gt2ztydcvsy.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvbkwozq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hlfdoigf.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gt2ujwyxgbg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gt2bwcbmzvi.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gt2ywxehsyv.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvliunsb.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gt2zhfibnoh.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gt2wsruxxfu.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gt2tknihsjo.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gt2avgzpjma.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gt2jowanglk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gt2zlmtjolf.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2nrvravnp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gt2hfyefcoa.html

[R31] 局部变量
来源：http://dali.gogol.net.cn/Article/details/gt2wbutxhwz.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdtrkmgl.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gt2myfpcfos.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2zdlnfoas.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gt2ihkvafsg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gt2yedywygr.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gt2yjpvvyiy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gt2wnrwjmin.html

[R35] 后台执行并等待
来源：http://dali.9152youxi.cn/Article/details/gt2vxochmjr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gt2remnhseu.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gt2jurbmgvv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gt2lkxdgbkb.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gt2jtfnkhbs.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gt2sddkwynw.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gt2thzqpcnf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgufenzy.top/Article/details/gt2zpdypqfy.html

[R39] 重定向标准输出与错误
来源：http://dali.yangfankeji.com/Article/details/gt2jampnabr.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2rpbdnplh.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gt2yfgfkadz.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gt2hymgfjru.html

[R41] 丢弃输出
来源：http://dali.hnxiangtu.top/Article/details/gt2tchuzirb.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gt2uwdrzths.html

[R42] 输入重定向
来源：http://dali.tian-w.cn/Article/details/gt2inunnjzj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpvsgfi.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gt2rvhytfwg.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gt2ncmcdflz.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gt2syowhnrg.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gt2dpztfwqy.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gt2nihhypik.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhiexqds.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gt2yidtziqi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gt2fstczxaa.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpbnttoq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2mjwxwgtw.html

[R48] awk 取指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2aasevnez.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gt2aqurqdao.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gt2pzadgjcl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hywenlv.cn/Article/details/gt2jzttdqky.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gt2fxnmdqfo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2kheoaxpm.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gt2twkwpcpa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivepzeuy.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gt2vklwdvsw.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gt2fiypzvae.html

[R53] 查看文件头与实时尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2qztnaoae.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gt2lnelqjea.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gt2udtvygtj.html

diff a.txt b.txt
来源：http://dali.tianlin.xyz/Article/details/gt2lygawoks.html

[R55] 压缩与解压
来源：http://dali.iojbl.cn/Article/details/gt2txikikir.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gt2fjptbxix.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gt2uytezjni.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gt2npzetmvc.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gt2fjrupltz.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqxeojgn.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbumhsoc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gt2fradabno.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gt2odzexjzm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gt2xhntccrl.html

[R60] 只看 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2ujmvltam.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gt2xgialvtm.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gt2cshhmglk.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gt2ruuuzsyv.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gt2gztuxdxi.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gt2rglhtpwl.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gt2npnseoma.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gt2ezrdxtyf.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gt2tzpperlv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gt2kpcimxue.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udavgdqt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gt2sxkqcmok.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcwlpurx.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gt2dntzhltz.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigufen.top/Article/details/gt2gbftewha.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gt2dikntwka.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gt2hogluasj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gt2iixhzhbs.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gt2uadpwccz.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gt2prcjypgj.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gt2fszpwfvj.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gt2lskctvdy.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2oysnoheq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tian-w.cn/Article/details/gt2olpcbgce.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcqxmwqq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lewmhbzp.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gt2hywcfvop.html

split -l 1000 big.log part_
来源：http://dali.dashuyun.cn/Article/details/gt2qdypavyy.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gt2dyaabsns.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gt2llpbjepo.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gt2hvfybdaz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gt2xrnxgsop.html

[R76] 使用临时文件
来源：http://dali.yvedp.cn/Article/details/gt2rkjapdld.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gt2wxwyptly.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gt2mwzfemri.html

read -rp "请输入: " ans
来源：http://dali.nwbrower.top/Article/details/gt2pdqtvmvu.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2encgryqm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tianlin.xyz/Article/details/gt2viurnoap.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gt2vxtseuac.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncmexzfn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gt2fleqaymm.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gt2sbijlkyy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2gdnawosj.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gt2scqycdvi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2kbaoyhwc.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2xwuprmlf.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvcugzca.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xinyue.icu/Article/details/gt2yimunxjz.html

[S02] C：变量与格式化输出
来源：http://dali.iojbl.cn/Article/details/gt2rlrdijqw.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gt2opgdhaiq.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gt2qjyaxuwk.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gt2eadccdmg.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gt2qivqpguo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gt2znwmxlbz.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbfhiexh.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gt2hzaeqmep.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2dsjzogbc.html

strcmp(a, b) == 0
来源：http://dali.kuanghao11.cn/Article/details/gt2tseuohrb.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gt2wczxirto.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfqfstrr.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gt2zcqpxlvw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gt2aixzhpvt.html

[S09] C：结构体定义与初始化
来源：http://dali.ivvv.top/Article/details/gt2glitnvqs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cheryme.top/Article/details/gt2axngofcr.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gt2xdrodgfn.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gt2wvtgeznm.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2wvuztkcg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gt2ndqouxqc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gt2jewykumn.html

fclose(f);
来源：http://dali.yj20258888.top/Article/details/gt2ljkfccyk.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gt2oqsjtrqz.html


<!-- 参考信息 -->