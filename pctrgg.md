代发 wailian999

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gtrvqzeqny.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkbkqlue.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gtgrnaukna.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gtnirbbjnr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtoumfdgug.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gteggmnxbb.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtwxvhbmnv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gtyzdtfeik.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gtjwxwsxgn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gtucxjltox.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtkauqpzgh.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gtantudtny.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xziqi.cn/Article/details/gtlzoghteu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gtzvnumezj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenlongwang.top/Article/details/gtehpicikq.html

[Q42] 连接条件附加过滤
来源：http://dali.haohaochexian.top/Article/details/gtwzpudwfn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gteicgckee.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gtyoygyfri.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gtewpnfsse.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtwzapcpef.html

[Q44] IN 子查询
来源：http://dali.andypj.xyz/Article/details/gtamperunw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gtkkjuawvg.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gtdbnkkrha.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtzagsicuy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hongshengwenyu.top/Article/details/gtozqwxnyn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzbhbejf.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gtrbvuqmnj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gtvtcaqkgv.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gteumzungw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gtflbrshmv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gtpgvjwtel.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gtdlbmkkbv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtnglvllyo.html

[Q50] 批量更新
来源：http://dali.ivvv.top/Article/details/gtauzprdqt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtqngdgcsg.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gtmmytlbmy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gtaxwhlgyf.html

[Q52] 删除指定行
来源：http://dali.yj202588.top/Article/details/gtinupbole.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtsgmuaxzc.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gtdgddsmyk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtevvvrluc.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gtbzinqqvc.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigfzy.top/Article/details/gtdjvuadzt.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmkhemkp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtgbowxpkj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sufxvd.cn/Article/details/gtcklmyvpj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.smart0.xyz/Article/details/gttyrouisq.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gtwsmzjtwr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtjhitmnqn.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gtcssfzuqk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtqbsoqdqw.html

[Q59] 分组内累计
来源：http://dali.gogol.net.cn/Article/details/gtxchoodnm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gthyygqlxs.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gtrswxpbjq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gtvtjeodir.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtcecnwvbz.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtxcnxwoou.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtuucrkyvl.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxgfjgpq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtwupxwfnz.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtdggykhhz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuanzhike.top/Article/details/gtemdroqvk.html

[Q64] 提交事务
来源：http://dali.sufxvd.cn/Article/details/gtusiuodcb.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gtmmlxudcm.html

[Q65] 回滚事务
来源：http://dali.chenjidiqi.icu/Article/details/gtsxjdanud.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gtknsmjvng.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gtakfotfmx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gtwovrccxk.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gtocpkxpky.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtczoddxpn.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtyjkndtvp.html

SAVEPOINT sp1;
来源：http://dali.ybcxt.top/Article/details/gtazxamyzw.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtzgboncow.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gtvwjdppan.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gtqeplkgnq.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gtkxzokmap.html

ANALYZE TABLE users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxraxhew.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gtpwrljovw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gtmdxiwxsl.html

[Q72] 查看索引
来源：http://dali.aibaodan.cn/Article/details/gtdrwkvbow.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtscgpazzu.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyqclexe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtggtmuaxf.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gtexdirykg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gtcbovaypr.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtmcmlpyqy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtufpzsrzc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258.top/Article/details/gtghvemhck.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gtwwxeifkw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gtwlkwlbdn.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gtvijoyhqb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtvdifyjyw.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gtgopqfjma.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gtiogykykf.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtjpgjaydk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gtcuewewve.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gtpvgcsyww.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gtzwkvrzgq.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxvqneel.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtebyluwrg.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gtgflmbpnc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gttqjhrsjb.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtcdethuex.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtpskgehgo.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gtabvslpjj.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtluhauvtg.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gtgqzafawp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gzhubu.top/Article/details/gtyuvodbgk.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gtpiouagut.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangshuangyany.cn/Article/details/gtpyfqdwzc.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gtxwdppmgq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.kuanghao11.cn/Article/details/gtkmzpjizu.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gtetsotdtm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtgadmfnio.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtixomjgvx.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gtfkpbyolq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gtyfyywsuk.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gtowryidpt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gttkupafrz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtgaskwozm.html

R. Bash 专题
来源：http://dali.iojbl.cn/Article/details/gtnffnxjtk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdxrotmak.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gtaaqyphso.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gtswbdqylw.html

set -euo pipefail
来源：http://dali.feifeiyinyue.top/Article/details/gtelpurdsi.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gtyfodcbmk.html

name="Tom"; echo "$name"
来源：http://dali.hnxiangtu.top/Article/details/gtsdmkqhtk.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gtvzcsvjci.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gthfenmfvv.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gtqluzqniy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gtfsjzxeuv.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gtlhozekev.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gtbcbcigks.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gtabpokqlz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtwbryzjiu.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvuvgsdk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tian-w.cn/Article/details/gtdjcctugm.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gtxsunmkxs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gthhcbyddq.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtokkrtlwt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jianghu66.top/Article/details/gtusgcwlyu.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gtgrfesazq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtqiskdvhr.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gtgmujunau.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gtsvramimr.html

start) echo "启动" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtonuvopjw.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtbuoposxi.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtaaeaocqr.html

esac
来源：http://dali.guannengcc.top/Article/details/gtemlcakeh.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gtnygluywe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtakjadwvh.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtqjesjqtj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtmbvzirap.html

[R14] C 风格 for
来源：http://dali.feifeiyinyue.top/Article/details/gtliezbkfv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtkblzedjq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gthldafvwl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvvoopbw.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtzesvrlnk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtzhzmeoki.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gtzfgrhcxh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.bjfxy.top/Article/details/gtwxwuoksw.html

[R18] 遍历数组
来源：http://dali.sweek.top/Article/details/gtolyxufql.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtsmazsefw.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtwzlaoawe.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gtucwiqait.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gtwluwbotg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtzkyztxpx.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtfcdeilem.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gtmbkcazgs.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtwnvxszbk.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtxragvyin.html

[R23] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtrvowjavn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gzhubu.top/Article/details/gthnidbsxl.html

[R24] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjssidjud.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmhrfibk.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gtoafsypzq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gtpeykmodw.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gtfoqrveyg.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gtmnuzcaif.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gtwsezobwo.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gtdupgaeio.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gtzpnckhwv.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gtegazcboh.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtkvizattu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtcmqyjsmt.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gtmgeilkvi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cdnleiting.top/Article/details/gtmsydmsjo.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtcgtqkryv.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtqizplnup.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gtbegwbanp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtaioukika.html

[R33] 捕获错误并提示行号
来源：http://dali.cucudq.cn/Article/details/gtreuguuzb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gtblazdryr.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gttwtoyfde.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtcyaagdgv.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gtrbaqmzzu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuetiantiany.cn/Article/details/gtjoliowjx.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gtnjfpyrff.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gtxxkboind.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gthtxpmhgc.html

files=$(ls -1)
来源：http://dali.hywenlv.cn/Article/details/gtrztnbbys.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gtlelhnums.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gtauqbbvoo.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gttbhigdss.html

cmd > out.log 2>&1
来源：http://dali.xylfe.cn/Article/details/gtnuvjalgw.html

[R40] 追加写日志
来源：http://dali.pycfn.com/Article/details/gttebvzeyq.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtpbbvjxde.html

[R41] 丢弃输出
来源：http://dali.nanxinkj.top/Article/details/gtjqegzgvq.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gtipnhalnu.html

[R42] 输入重定向
来源：http://dali.yongpay.top/Article/details/gtyiilmdgx.html

wc -l < a.txt
来源：http://dali.guannengcc.top/Article/details/gtsijqnqov.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtsnufibnj.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtqmaqvsaf.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gtqbiqkxso.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtpigkdudt.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gtfqzdhoth.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gtkiwwunps.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gtdivkflna.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gtlaamdgll.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gtoiggfuoa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtjpftygoh.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtzshswbla.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtpuprhmjf.html

[R49] awk 带条件
来源：http://dali.aibaodan.cn/Article/details/gtodtmwdpm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtnfzdvtwn.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczkrljbz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtwycmplmu.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gtzprurhai.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjbfhink.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqegmqyn.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtvpupadzx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhixingplan.top/Article/details/gtrdowgodd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.mhx1999.top/Article/details/gtqnctpqou.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gtitfdpgmf.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gtngndoysy.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhyelltc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gticdhwpsm.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gtxeidfysc.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gtwvqnpqws.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gtyoqqsyvl.html

ssh user@host 'uptime'
来源：http://dali.guannengcc.top/Article/details/gtntzsmixz.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gtucjkkdxj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gtdjulnojm.html

[R59] 发 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtcmjzuahy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtwrbfnyjd.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtkpkrnxrg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gthfqrntto.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gtaofrnrkx.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gtvhqjcagv.html

[R62] 找最占空间的文件
来源：http://dali.quarkkingdee.top/Article/details/gtoojpovhk.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gtlgogyaux.html

[R63] 内存与进程
来源：http://dali.chenlongwang.top/Article/details/gtlfirvczn.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gtbvmjtkmp.html

[R64] 结束进程
来源：http://dali.cucudq.cn/Article/details/gthhhortap.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtcviaqjwj.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmjbywvy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gtkrbihxpd.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtntwpwbod.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtosqqiqgy.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gtievqdudq.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gtkhvzfezr.html

[R68] 计算文件校验值
来源：http://dali.hnqzz.top/Article/details/gtzroifcer.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dashuyun.cn/Article/details/gtafbfgqtl.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gtabrnnbpb.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtupgrqoye.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gtdofvkxkz.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gtyoirkavl.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtdpafctja.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gtguamwyop.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gtbyqyxrfq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtxqeccuob.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gtxalqxhhm.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gtwaytxxtc.html

[R74] 批量重命名
来源：http://dali.nwbrower.top/Article/details/gtldrkvzbl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gtraqhkwii.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtkppbyuev.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gtzfoknrsw.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gtexqajuly.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtzahflxhq.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtfhroappn.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gtwnopsbpq.html

[R78] 交互式菜单
来源：http://dali.0kj1m.cn/Article/details/gtlalawlmt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtourzfsdb.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gtqslgavhv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gtaphsqlpl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gtitmutyaj.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gttydvuqua.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtmzujpvqz.html

S. C / C++ 专题
来源：http://dali.xuanzx.com/Article/details/gtnhfzlnuw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthumgmoxs.html

[S01] C：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtphwaznmq.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtkwxuwiui.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gtiksueccr.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtauiybwau.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gtehydmtoo.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqnzrtig.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gtaxjfnwkc.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gtxnuyjydd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gtymhfimzv.html

[S05] C：字符串长度
来源：http://dali.bjfxy.top/Article/details/gtzkzrnyvf.html


<!-- 参考信息 -->