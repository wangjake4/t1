代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.yonumen.top/Article/details/gtbttwtlao.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gtrdrtcnfx.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtvituzctu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gtcfezaqwl.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gtejmvymuw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gtxtvffqgo.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gtfkykcjfb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtcrqrgoqk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtkjtynjfh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtfnvpyftc.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gtwdfudnse.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gtbbetmvdw.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gtfxhpvqwa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hywenlv.cn/Article/details/gthdcsucoi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gtisityqje.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gtaqprbrii.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gteivheufs.html

[Q50] 批量更新
来源：http://dali.fzhhl.top/Article/details/gtcnxxbrxk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppaxiojv.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gtqlgzuota.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtpfstroog.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gthtbtbrjl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtqxaoobfp.html

[Q53] 按条件删除
来源：http://dali.chenzaomai.com/Article/details/gtsfvwpexz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtcgsnwwlz.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gtemxutfan.html

TRUNCATE TABLE logs;
来源：http://dali.pengpengdd.cyou/Article/details/gtpolsmtmv.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gtaldlksrl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtmcpomrce.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gtfmpiihpe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtuwrglvpd.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gtialjfyqr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtwxrtbxup.html

[Q58] 累计求和
来源：http://dali.haohaochexian.top/Article/details/gtppbhwahb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtmnjtzbof.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gtwqwfuzcf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtcqcdzmpj.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gtstveubqb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gtnwcuekhm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtgwzyulzx.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gtnmxxwxgs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gthikuflmx.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtglmnkscp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtczdqbgec.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gtcokmdgxx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjxkoqez.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gtajmudhdb.html

COMMIT;
来源：http://dali.sufxvd.cn/Article/details/gtwlkhkvlb.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gtzwuxppvs.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gthrcgltvz.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gtiyyauchu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gtrnoakywx.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gtelhrunwl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gtzgionauk.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gtkojrtrlt.html

SAVEPOINT sp1;
来源：http://dali.zhengqikj.top/Article/details/gtivpkjgtr.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gtrdkkzzvr.html

[Q69] 查看执行计划
来源：http://dali.yangfankeji.com/Article/details/gtlxzlwqtc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfwdewqm.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gtpnnxfuzi.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gtsweevmvq.html

[Q71] 查看建表语句
来源：http://dali.chenlongwang.top/Article/details/gtwckbhsbd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gtenhhjsun.html

[Q72] 查看索引
来源：http://dali.meibo888.top/Article/details/gtslwnnfzh.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gtffkjcktv.html

[Q73] 查看表状态
来源：http://dali.vqdsnc.cn/Article/details/gtbmxwcwsq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pycfn.com/Article/details/gtbzzqdmtr.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gtswdnfsku.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gtmmljkeey.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtnshiqemv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtpqapvbkd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gtadapxjbb.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnuakabt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gtbylorijc.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gtrhfmsxjd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gtyqxzumvs.html

[Q78] 当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqdhbmds.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gtxcutnlll.html

[Q79] 字符串拼接
来源：http://dali.ybcxt.top/Article/details/gtpnofbrac.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sweek.top/Article/details/gtjexkkpta.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gtxrhmcldv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtedsxuzda.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtaazylbnb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtwsynucvz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gtantielvm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtdfbixbcr.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtoegmikzp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtvxykjmsj.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gtiwbuqggi.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gteintdlai.html

[Q85] 数值取整
来源：http://dali.jyoumei.cn/Article/details/gtghpkyezb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gtmfyglfib.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtisuuxgxi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shzxlz.cn/Article/details/gtqbwzhzwe.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gthrokjrax.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtadbwtqce.html

[Q88] 行转列（条件聚合）
来源：http://dali.ydzc1.top/Article/details/gtgsyhxtbj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtfmddbdjl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtywdbfzpn.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gtjuiwtqfq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.birdmap.top/Article/details/gtxuxguzjl.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gtvyayemfu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtneesysky.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtftnmomey.html

R. Bash 专题
来源：http://dali.hnxiangtu.top/Article/details/gtlswxcnmv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtakpplwfb.html

[R01] shebang 与严格模式
来源：http://dali.gzhubu.top/Article/details/gtrywtkjlk.html

#!/usr/bin/env bash
来源：http://dali.jiagoushi.top/Article/details/gtrczvsppa.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gtdvxgxakm.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gtrownkavf.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gtuzxpvkdk.html

[R03] 只读变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtdeimqglg.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gtlynfxowt.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gtvwyafobr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gtkxviarjs.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gtrrmoofva.html

name="${1:-default}"
来源：http://dali.quarkkingdee.top/Article/details/gtemcqpzhz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtdttuhblv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtuismavkk.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gtgjkzobeg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gtigskldub.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtwbvhiasy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gtqfyirhfj.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtulsfsusc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gtjubdzrjc.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatsyseor.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnqzz.top/Article/details/gtgdzjours.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzskyoynw.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gtyiwpffie.html

start) echo "启动" ;;
来源：http://dali.dashuyun.cn/Article/details/gtvnpgnbuj.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gtvfyutmlj.html

*)     echo "未知命令" ;;
来源：http://dali.xuanzx.com/Article/details/gtwjmasras.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkdwlwjr.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtfagwzxxo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ivvv.top/Article/details/gtqxkejdox.html

[R13] for 计数循环
来源：http://dali.meibo888.top/Article/details/gtbzjoejun.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtdmfrepss.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtehqyunli.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtbfdgvgxc.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gtockdfjci.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvtrodnf.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtkgrvmqky.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gtepxsnnns.html

[R17] 数组定义与取值
来源：http://dali.gogol.net.cn/Article/details/gtuecxemrm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtmbobbzvu.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxlrkavv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gthmobrkhx.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gtnstfngmw.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtjostozrj.html

[R20] 关联数组（字典）
来源：http://dali.gaohongyu789.top/Article/details/gtsnomgzwp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gtsaumwqko.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gtgxvblfzp.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gtmfhorklt.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gthefcdmao.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gtabybicxq.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtoecekmex.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtovdzjitx.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtwzwbcmdb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gtglonnvvb.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gtgsasdeev.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpbiswsh.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gtdbebvwcy.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gtxfmqweqn.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gtmowjihld.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gthqcxieyd.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gtchzgxqsa.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gtkaxcbkem.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtcllpaxad.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gtxypipzoe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gtwrmuclqb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gtumvquucb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtawlcbfmf.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gtcjwrbktx.html

[R32] 参数个数校验
来源：http://dali.shzxlz.cn/Article/details/gtqnfnhrwh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gttbqlavcw.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gtqeyjypkf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gtbcbhkymo.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gttlqkugvn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gthccnuvwc.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gtzzktpgdo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gtvmqbshni.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gterhzjmil.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtmvqpqjzk.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsodcgxe.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gtknvkbiug.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gtaduxyakc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jyoumei.cn/Article/details/gtkuavrpwu.html

[R39] 重定向标准输出与错误
来源：http://dali.shangyingyoupin.top/Article/details/gtsotgiack.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtbamcontr.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtdjllwefl.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gtslrqhxzk.html

[R41] 丢弃输出
来源：http://dali.xinyue.icu/Article/details/gtwfpqabuj.html

cmd >/dev/null 2>&1
来源：http://dali.birdmap.top/Article/details/gtjwsyuqtu.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gtphvdbudr.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gtdfgtmlkh.html

[R43] 按名字查找文件
来源：http://dali.hysaishi.cn/Article/details/gtwghkwygy.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gtunjakkuf.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtanwxurmr.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gtjsjpavjn.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gtufdalcgz.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gtuehxwyyy.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gtaqknbelw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gtuoygadid.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndgwhwsm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sweek.top/Article/details/gterhwnrsq.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gtaqwemtbj.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gthieyyrlv.html

[R49] awk 带条件
来源：http://dali.zhoulong.xyz/Article/details/gtpkmbyppq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodvbijca.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gtsdnvzcvf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtggvyjjri.html

[R51] 排序去重取前几
来源：http://dali.nwbrower.top/Article/details/gtncevhuxi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoppyskv.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gtbeveniol.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtjzfxbzsn.html

[R53] 查看文件头与实时尾
来源：http://dali.andypj.xyz/Article/details/gtgupqcsrf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gtuunmiszz.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtmuqmiftq.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gtkgzpkmsf.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gtsuneedqb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pycfn.com/Article/details/gttqqtthzs.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtulxkvuvx.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gtkacyvqsf.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gtgymbgdjg.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtnwqcgqdw.html

[R58] 下载文件
来源：http://dali.chenlongwang.top/Article/details/gtduqweula.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ivvv.top/Article/details/gtjibwvfic.html

[R59] 发 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtiadocldu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gtgsvcuvpa.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtkscyehku.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gtuovpfjdu.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gtuvcjswlr.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtcfurwxmt.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gteatiheuz.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooihvlsq.html

[R63] 内存与进程
来源：http://dali.sufxvd.cn/Article/details/gtycyrllcv.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gtikhgcdou.html

[R64] 结束进程
来源：http://dali.gogol.net.cn/Article/details/gthxipekqj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrdqssyi.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtisekxozo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuxming.cn/Article/details/gtwsajajyh.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpombmwme.html

crontab -e;  crontab -l
来源：http://dali.zycfv.cn/Article/details/gtulzotmcg.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtbrksqdle.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtudfnkhww.html

[R68] 计算文件校验值
来源：http://dali.jyoumei.cn/Article/details/gtystvxyyp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gtidviafki.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gtczlotnzr.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gtqjrtcdib.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gtlzualoxn.html

date +%s;  date -d @1700000000
来源：http://dali.aibaodan.cn/Article/details/gtuvbzglwq.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtcnonpuqm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gtvbqpjvdr.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbertbbuo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtskhgxqph.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gtkifhttsd.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtqqsmdshu.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gtztrjarnt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gtxsulirkf.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtrcxgtyjo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gtbhlchwtu.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gtuualpeqv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtkbmjqegl.html

[R77] 读取用户输入
来源：http://dali.ivvv.top/Article/details/gtzhdmywmu.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtwfnnczte.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gtcysmgqfo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hongshengwenyu.top/Article/details/gtaeaqylkk.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gtvxxvngzg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtctenlmsh.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gtinsqhiba.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gtazfkfgow.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvyuyzysr.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gtutjrrgqd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlufsdnau.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gtfloiamjf.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gttekrkkpq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtsoyqffky.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtobhiaqdl.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gtqrixzejv.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtpwvvhsnu.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtaenhkwba.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtrgttgznj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtdehgislh.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gtdwivjomh.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gtadbponar.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gthtgoapbf.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gtdpltoiya.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvgoxjyf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtooqwavaz.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gtjwmekiep.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtlmsichkb.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gtxpmbfogi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gtkavgjkix.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtqkyrbqds.html

int *p = &a;  *p = 5;
来源：http://dali.ybcxt.top/Article/details/gtuplblptf.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtxhtqudzj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gtbyolfjcq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtcagvjasb.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtpgfbuxyz.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gtzssjtxsa.html


<!-- 参考信息 -->