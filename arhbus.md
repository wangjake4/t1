代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gt2xiwknkof.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2fufcqawo.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2emypdthx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gt2qdpyaqgp.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gt2zhirxidi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqxnrqbz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gt2zaqsaevc.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wilojnum.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2pxfocdaf.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gt2lrcvrdya.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.svipenyu.cn/Article/details/gt2cupesthw.html

[Q51] 用子查询更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcptvvon.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2oijujwzb.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbknvepz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2qxswrnfx.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gt2rrgzsewe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gt2erliytga.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gt2dzegpuhy.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gt2nuxwedhh.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gt2ywmnuqlf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2eypgudnb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gt2sfisnjfm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2ynuwfvbz.html

[Q57] 行号
来源：http://dali.cucudq.cn/Article/details/gt2tgahymgu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2hbkjevwt.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gt2tvjapirj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2twtgsvdn.html

[Q59] 分组内累计
来源：http://dali.sxryk.cn/Article/details/gt2wlmvknsc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2pqobleqz.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gt2tgfpnhbe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gzhubu.top/Article/details/gt2eerxoccx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2crzhxxgw.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gt2oivruqas.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2tkoutjak.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gt2irujvrxs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2jmogwbuh.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gt2poesejlm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gt2lrpdeflq.html

[Q64] 提交事务
来源：http://dali.kuanghao11.cn/Article/details/gt2qhcvscnz.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gt2ioyhxbev.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gt2ojxhabfl.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gt2mbkmsfkt.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gt2wmiowyxf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zdqjudy.top/Article/details/gt2lplvtlaw.html

[Q67] 设置隔离级别
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjluyzmg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gt2drnkkeic.html

[Q68] 保存点
来源：http://dali.gzhubu.top/Article/details/gt2rzafhtyp.html

SAVEPOINT sp1;
来源：http://dali.aizwys.cn/Article/details/gt2joskplks.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lisnhyux.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gt2ghyowilr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gt2iclumzdk.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gt2zttsawpp.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gt2woqqhdjw.html

[Q71] 查看建表语句
来源：http://dali.gaohongyu789.top/Article/details/gt2dacaoauc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gt2wyuvooko.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gt2xdsjwllt.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkwxygdk.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gt2iilklyqg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkfdkolm.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gt2roxvebqg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gt2pnuwbzlw.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2kfgvcdup.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ublumvvj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhongyouzk.top/Article/details/gt2hmqsjlkt.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gt2seozuzwh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tian-w.cn/Article/details/gt2dlykvnzu.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gt2qfyhhnfk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gt2icfpstgv.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gt2tvvsjdyb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gt2pxbgdqoo.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2isldfjcf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gt2syragkim.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gt2vjewycgp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2yqvifwyz.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gt2ozsdvebx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2pimwfbkr.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gt2harmiaub.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2vawvbdgz.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqzuchfn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2lyfgwtxu.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gt2yilblbxa.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2yxcdifme.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gt2fyttghra.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yangfankeji.com/Article/details/gt2oyresxhi.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gt2njqutwgb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gt2gwuuwixp.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gt2txxlqymi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gt2ejyowaua.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gt2fhacpmvc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jianghu66.top/Article/details/gt2dnaajeav.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2czwmbwly.html

[Q89] 判断表是否存在
来源：http://dali.guannengcc.top/Article/details/gt2dzyxkijh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txtthdgv.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gt2lrkcoymb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gt2bezhpnld.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2fathnwil.html

R. Bash 专题
来源：http://dali.jianghu66.top/Article/details/gt2npjguqoq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2cuvaxrlt.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gt2jsfisado.html

#!/usr/bin/env bash
来源：http://dali.dashuyun.cn/Article/details/gt2fmpdjkpw.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gt2hushyujn.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gt2pndhsqjs.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gt2ooqkhtdk.html

[R03] 只读变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmyofrmf.html

readonly PI=3.14
来源：http://dali.xylfe.cn/Article/details/gt2nzdntcks.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynikuqlb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gt2oesecaiu.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2sdmkocnm.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gt2nvnbanxa.html

[R06] 判断命令是否存在
来源：http://dali.daria6918.cn/Article/details/gt2tefwfszv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljtrezjy.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gt2sdzodnfk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gt2vgxyztqf.html

[R08] 数值比较
来源：http://dali.aizwys.cn/Article/details/gt2fpmwvafi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2tcgynydl.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2phsrxqvq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2orzilojl.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gt2ekalzsot.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gt2osffnrqk.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gt2xdvxlodg.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gt2honydjbl.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gt2hwgufiyc.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gt2hmxiqmoj.html

*)     echo "未知命令" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2mgczlcmx.html

esac
来源：http://dali.cqqwz.cn/Article/details/gt2fpsqqiuf.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gt2ebfettpf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gt2cuapcgoa.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gt2kaudynwn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gt2xrwxosjz.html

[R14] C 风格 for
来源：http://dali.birdmap.top/Article/details/gt2xaqrgysq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gt2nqjqhfgb.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2ycwqatef.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.snrcjt.cn/Article/details/gt2yvapmpbr.html

[R16] until 等待条件
来源：http://dali.wangdashe.top/Article/details/gt2xmexasjz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gt2svdobhxj.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gt2nhlxxqjx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gt2noouewmc.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2gahsvrja.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.c1oappe.top/Article/details/gt2kfusrhgr.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2kbibabks.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gt2rktgugfi.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvgfetfx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jiagoushi.top/Article/details/gt2xrhydqiq.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gt2trfeoqlk.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gt2tcdmtxvd.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gt2fqkbuuww.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gt2uggvxyvx.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gt2drkhjqjg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258.top/Article/details/gt2ynyggvlb.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2wyqrhsac.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.havefunace.top/Article/details/gt2gcdbclld.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ektnxjjn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lyvlmjdt.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gt2kbtwwywf.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gt2ughawjee.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gt2ilflejkw.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gt2cymtwcpp.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gt2thslwqdk.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gt2lzofyove.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gt2ugtzjjvf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbixjksq.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gt2pmikbvzb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gt2iqitlavx.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gt2qsarkjgf.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gt2afproset.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gt2ebygizvp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gt2jahcnjff.html

[R33] 捕获错误并提示行号
来源：http://dali.fengsongda.top/Article/details/gt2wkjjlwpn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gt2fkxijwyq.html

[R34] 退出时清理
来源：http://dali.pycfn.com/Article/details/gt2jevdfywd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gt2llkloqfr.html

[R35] 后台执行并等待
来源：http://dali.kuanghao11.cn/Article/details/gt2mczbduir.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awomvyfh.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gt2nirmpkwi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gt2ktfrprzd.html

[R37] 把输出赋给变量
来源：http://dali.shzxlz.cn/Article/details/gt2akdduekj.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gt2qwqnsdhi.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gt2jhqlhfpa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj202588.top/Article/details/gt2ctxaoiqo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gt2mpnsstfe.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pyaclgtq.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvbjiles.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gt2ypmjrenj.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gt2naftvjks.html

cmd >/dev/null 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gt2srsvbpmz.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gt2bqwvjjiu.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncirzchj.html

[R43] 按名字查找文件
来源：http://dali.svipenyu.cn/Article/details/gt2sxnuoqsf.html

find . -name "*.log" -type f
来源：http://dali.zdqjudy.top/Article/details/gt2vbzefznb.html

[R44] 按修改时间查找
来源：http://dali.c1oappe.top/Article/details/gt2iiiawqhv.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gt2xqtcqjbx.html

[R45] 批量删除
来源：http://dali.nanxinkj.top/Article/details/gt2xozlcjaz.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gt2wbffcieu.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gt2srvdenxk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gt2whmjzkrl.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gt2lkrarqls.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqqtinoj.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gt2jhisnyvm.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2aafgvmko.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gt2msrymkdj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gt2onfajhrm.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gt2xzhujmsk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2owldzlmh.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gt2lbfeqlhx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gt2mogsgqek.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gt2ggbctwge.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2rjdpkcaf.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gt2dncjsjxw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gt2iwmspnwx.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gt2vpsakymx.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gt2gflaawmq.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gt2svlaarse.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gt2woohrdht.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gt2fquqlxyp.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gt2ofqnwrvq.html

[R57] 远程执行命令
来源：http://dali.ivvv.top/Article/details/gt2luqroqaa.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gt2pygctmsd.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gt2jhiwdnzt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gt2qenkqthd.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gt2kxpptvwj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gt2whftderv.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gt2jobrciqw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gt2vxacpxlq.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mkutsbrw.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gt2hlbiacvr.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gt2nceajlqt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gt2tceylvoj.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gt2cfxakxdm.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gt2iqquwxlk.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gt2qqpadqfn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gt2amgudryw.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gt2uuswbksn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gt2axjfcgid.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gt2ceacbpwz.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gt2naanbbyn.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gt2dwybpqrl.html

openssl rand -hex 16
来源：http://dali.cucudq.cn/Article/details/gt2ljqddeow.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gt2ycuhidcm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gt2xckidwle.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gt2gjulavha.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gt2yccbxedr.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gt2vcytagyp.html

date +%s;  date -d @1700000000
来源：http://dali.nanxuanxn.top/Article/details/gt2wqkuywai.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2dkygxjrx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jahzdfsw.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gt2anskvuqs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2gebnjkns.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gt2ylxqpadm.html

split -l 1000 big.log part_
来源：http://dali.shzxlz.cn/Article/details/gt2asyfaxmb.html

[R74] 批量重命名
来源：http://dali.nanxuanxn.top/Article/details/gt2yumeachk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2kfhighwi.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbfinnpy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gt2hvdfomno.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzyuoxwd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gt2gegimnxc.html

[R77] 读取用户输入
来源：http://dali.bjfxy.top/Article/details/gt2bajjqiet.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gt2hliihhxn.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gt2tbhqlbfh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuvczcug.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gt2ymmdxrrj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gt2nnjxqrhr.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gt2bjzvhmkv.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gt2xnaejrbh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2zepyccnl.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gt2nfrqascm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2oxnjumve.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2dnloeodw.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gt2ykpifiqg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfmrqfjw.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2mipmuenj.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gt2dsodbtlh.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gt2kpbkchjz.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gt2hoxqufwg.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gt2kiuofubv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gt2zjbsqhur.html

[S05] C：字符串长度
来源：http://dali.ivvv.top/Article/details/gt2nnrxlddy.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2iqrgyocd.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gt2tgonotuc.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gt2kikdqxzp.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gt2hbekjiue.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gt2nnxosgbx.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gt2untinwzb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jihuzhgt.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gt2vvgempdc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gt2glwzufya.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gt2mxzcxtni.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gt2alzbqwod.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2tlagjfni.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gt2jpuskvcr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gt2daygbgvr.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gt2hvjyeroq.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2ipvjgdxz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2rxcfmgwe.html

[S13] C：宏定义
来源：http://dali.316326.xyz/Article/details/gt2tafkcbhe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqguvcnu.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gt2kipubtwb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gt2rsymzigu.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2cmjvjnwd.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gt2zxdlobov.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gt2bbpdzwjl.html


<!-- 参考信息 -->