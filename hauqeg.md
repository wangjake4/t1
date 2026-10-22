代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtpdhtptxn.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gtyxrbffir.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtdrhjckkg.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gtzakwlcib.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtqizoofpp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gthmgwucbd.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gtxmyjnxpr.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gtuhgxpezu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtysjtzcpa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gtbipkirls.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtsqegunvf.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvykjxjeg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtxwzlrshn.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtglogydhy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtyxazbkgj.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gtksvruwtu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtvhimysou.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gtgrmidenx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtetfweeon.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtewbuwznk.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gtbkyaqwfk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtoeikwthi.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gtoxgbfvka.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtikhtjrdz.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gtzwuaweuo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gtqxsfymnu.html

[Q64] 提交事务
来源：http://dali.hywenlv.cn/Article/details/gtkuqdjasd.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtxwsimita.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtnprpkaye.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gtuxxhkbuo.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtjosxpcnp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sysykeji.top/Article/details/gtlafqpjjy.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgdodtqe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gtqfbhwthw.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gthzdxycnk.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtikdamjle.html

ROLLBACK TO sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvgllofz.html

[Q69] 查看执行计划
来源：http://dali.yueranfly.top/Article/details/gtuygahscn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gtggbqqlry.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gtxynswsgn.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gtnhxjviib.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gtiukmcrpg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.0kj1m.cn/Article/details/gtoezfiecq.html

[Q72] 查看索引
来源：http://dali.redwolf501.top/Article/details/gtnwnqmaez.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtmjrowrfc.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gtsrbzyqzm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gtrohrsnrr.html

[Q74] 强制使用索引
来源：http://dali.aizwys.cn/Article/details/gtwqdyuzik.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gtpfnbxvxf.html

[Q75] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtxwjbrwwo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gtxvfarfig.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gtnsjnxciq.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gtbkczkrse.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtpgfmdwiy.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gtkpbcdgiw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gtxdtghcby.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmlvupug.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gtoudvfsef.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gtfyjmoyks.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gtvkycwvoa.html

[Q80] 字符串截取
来源：http://dali.ehwqpu.com/Article/details/gtrahjjpcg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtsyahtfpo.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtunrjlmzy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtoswcblea.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258888.top/Article/details/gtmwsdbxwg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtutdrfhaa.html

[Q83] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtembkenxq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtbvxvfnze.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gtadaielsd.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtvsrsckot.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtczrlwnci.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gtzganicsq.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gtlqmngwmh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gtllvjqpgv.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtinpwrocu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yangfankeji.com/Article/details/gtfhzhkkqh.html

[Q88] 行转列（条件聚合）
来源：http://dali.316326.xyz/Article/details/gtstpxrbpd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gtyovbpovj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyrvkwir.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gtcfxjuwnm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gtskgvpetw.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gtksuingji.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hysaishi.cn/Article/details/gtoszhzqif.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbcpmxhrh.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtgnsntyaa.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtenjatblq.html

[R01] shebang 与严格模式
来源：http://dali.ybcxt.top/Article/details/gtmilfhpay.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gtnxtkffww.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtxdpzlbvf.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtroeamafi.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gtgornnqri.html

[R03] 只读变量
来源：http://dali.shuidangran.top/Article/details/gtclgpggpr.html

readonly PI=3.14
来源：http://dali.nanxinkj.top/Article/details/gtlctjncvi.html

[R04] 位置参数
来源：http://dali.daria6918.cn/Article/details/gtgwtudvym.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gtnmkubbzs.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtdwnuxazv.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gtwypaxlla.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtlbmyqdky.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtsgykqpys.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtycykbtki.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtzxbgshoz.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gthqlsoedg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gtletiymsg.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtyxflohhw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gtdnkzafhw.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnnuptdg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gtmcvqjbax.html

[R11] case 多分支
来源：http://dali.sufxvd.cn/Article/details/gtwuafbpos.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gtegrhexsp.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gtwkvrjzuu.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gtytnxauts.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gturqcrocv.html

esac
来源：http://dali.meibo888.top/Article/details/gtnkvlzsae.html

[R12] for 遍历文件
来源：http://dali.cucudq.cn/Article/details/gtkrogaevp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gtzvcdjpth.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtiskxjvkd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gttvdpcorn.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gtcfpmbpye.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtriplensc.html

[R15] while 逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtnaucuzyn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gthjruotij.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtgkqvyqrk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtidaovwkk.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gtqsapjsot.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gtebxqnxsr.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gtvhnrmutu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gtxebwjtuv.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtqkelokfi.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gtxbawunen.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gtsmmypeir.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvqodvew.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gtsifomupv.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtbteamttr.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtvkypumuq.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gtptbmqvsu.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtihdeguni.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gtiysgzjdy.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtozgsfwpc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yongpay.top/Article/details/gtfbzwnxul.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258.top/Article/details/gtkzjezbpb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gtluuatpfg.html

[R26] 命令替换
来源：http://dali.xuanzx.com/Article/details/gtvwkmrtat.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gtlnmqhjfl.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gtiqjmxazb.html

echo $((1 + 2 * 3))
来源：http://dali.c1oappe.top/Article/details/gtekkxrdrk.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gtwqoyehzh.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gtptsroucn.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtzafdmlko.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xylfe.cn/Article/details/gtmtocnkwk.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtxvasmwci.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gtwwykqvvm.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gthnxpprpj.html

f() { local x=1; echo "$x"; }
来源：http://dali.316326.xyz/Article/details/gtyglkvdbd.html

[R32] 参数个数校验
来源：http://dali.hongshengwenyu.top/Article/details/gtqftymsxm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtbhuvdauz.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtbjpaleoj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gtnmlltoij.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gtgskdtdpz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gttmomusrd.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gtjahewawy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gtbvwnklgp.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gtwxytjakr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtohnmcwqf.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gthbvqtkqh.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gtxxqjwegz.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gtzxjfwcte.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gtabidrbdy.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gtqixmsgrn.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtdilnejcy.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtuiymechn.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gtlzxccvyf.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gtuwnzsgda.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtsaimouvc.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtjjapacnu.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtwbbkohcn.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gtujvgjjib.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gtghlqqnvo.html

[R44] 按修改时间查找
来源：http://dali.chenjidiqi.icu/Article/details/gtsjvkwmyr.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gtoerubwjq.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gtkawucqxz.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtxizvwkvk.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gtftcemgkk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gtvxbbgmtc.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gtmjwwivgh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtrgneslzg.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gtyagmbizk.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtussawamt.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqyhrzdk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gtpwoqqfop.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gtoijfwken.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtyzdbvrrx.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtfwvmcxzr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gtgrgiqzql.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gtxqkfvpdg.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gtjmowlseu.html

[R53] 查看文件头与实时尾
来源：http://dali.andypj.xyz/Article/details/gtvgjncwmt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtdiwjzevi.html

[R54] 比较两个文件
来源：http://dali.hnqzz.top/Article/details/gtbegenrcx.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gtuifcdhsc.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gtrckpular.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtupbskmqe.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gtcgrtnmwe.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gtfxbrpbfo.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gtngqwhpgv.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gtnmtvadsu.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gtmqqmqnzu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtevigynlc.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtlddptfhs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtbboftvih.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtkrpprsuk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aibaodan.cn/Article/details/gtvucdcmsx.html

[R61] 磁盘占用
来源：http://dali.cheryme.top/Article/details/gthhaerrzi.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gtkhhqzgvf.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gtmtqrulqj.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtecwgvcfx.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gtwkoyhvfz.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gtunsxfppf.html

[R64] 结束进程
来源：http://dali.meibo888.top/Article/details/gtcihhlfaz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gthlbhjqtm.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsybociy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gteqvullru.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtbtoyvhlf.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtslorpdsw.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gtfqkjskbo.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gtwqzdqujw.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gtkuxnqnrd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtihgeqkqe.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gtpjvexpuw.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gtnktqxdyk.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gtmddvyrkj.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gtcufmegvj.html

[R71] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtkygeqkon.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gtfwrmuqad.html

[R72] 等待端口就绪
来源：http://dali.c1oappe.top/Article/details/gtcpytocgv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvtytapp.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gtlotkwrzb.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gtmfbfkhww.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gtgzwrkzrd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gtyllyjgub.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gtmuyrbpsk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtynssaxrw.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gtzeorwuvr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpzazbun.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtfeustndx.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gtuupzusyf.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gteyebfpgx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtwvtquced.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gtewdwmybi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gtmjwlofqa.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gtqeafwihe.html

time ./run.sh
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmlrjsdb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinnivzdx.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gtukqnpkfj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtnmorlkly.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtiwbroxjz.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gtxstjlqta.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.haohaochexian.top/Article/details/gtbmmvgndb.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtmqizpzjc.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gtfepceerw.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtjsbthgqt.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gtbsunmlxp.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gtxwszpbmm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gtdbowbzdz.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtfmgempno.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtalfukspw.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gtnmsxvgyu.html

strcmp(a, b) == 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptuuierw.html

[S07] C：数组遍历求和
来源：http://dali.dashuyun.cn/Article/details/gtbspmcnhd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtvyxkkszd.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtcsnyjaps.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gtrkqygfmm.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gtqcepkvzz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gtsewlsbui.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gtlbwbfskc.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gtcppkmdzc.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtoquuyaeb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gtrtnegxjy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtkcoqqzpn.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtfeucuchw.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtpftcckqu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtacjqbvzb.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtkhsugqvc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gtdyjyherf.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtyzxdmplc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ppjwa.cn/Article/details/gtedopvgwd.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gtznekzqrm.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtjvpqomtk.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gtgrqnnoxj.html

x |= (1 << 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxqdvmph.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtkvxrbsez.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gtowykashw.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqrbisfc.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gtbmzdxbyr.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gtfhwutizc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtpvcmbwwp.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtenwxawet.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gteynvufbh.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gthcicrnza.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gtbvuowwot.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gtdfelytaz.html


<!-- 参考信息 -->