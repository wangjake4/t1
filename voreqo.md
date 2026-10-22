代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnffctlf.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gt2roqdyecw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gt2wijudcxd.html

[Q51] 用子查询更新
来源：http://dali.zhengqikj.top/Article/details/gt2wgzcelmo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2zpwslbaq.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gt2uumczgaf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2qjyislhr.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gt2gcttohsq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gt2oupuxwus.html

[Q54] 清空表
来源：http://dali.dianchejie.cn/Article/details/gt2drdvfyls.html

TRUNCATE TABLE logs;
来源：http://dali.zhixingplan.top/Article/details/gt2wiowfyim.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gt2hhkcanxg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daria6918.cn/Article/details/gt2ggcpyabb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gt2worbycnc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2isapyqfd.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gt2hpkrbsdp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2hqgguekv.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gt2xwoniluv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2yalrulen.html

[Q59] 分组内累计
来源：http://dali.kuanghao11.cn/Article/details/gt2sagtakdh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2igbtrvnr.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gt2ehdiblsd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gt2xhjljysk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2hxxysjrf.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gt2deqzkgno.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwdgphlg.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gt2pwuesfgx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2jqnwoahb.html

[Q63] 开启事务
来源：http://dali.jlsjyb.cn/Article/details/gt2ulflkton.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gt2bsxnboee.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gt2tnzjlunv.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gt2lafxvjxc.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gt2ktmcbplm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoucdex.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pggslgbn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ehwqpu.com/Article/details/gt2mcynyjrp.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jchhvcug.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sufxvd.cn/Article/details/gt2jzbugjpm.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnigmtna.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gt2fjxizqdq.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2jloldzjt.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gt2juayllxa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangdashe.top/Article/details/gt2rbrokgbt.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhernzhj.html

ANALYZE TABLE users;
来源：http://dali.shzxlz.cn/Article/details/gt2xbfgsnsz.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gt2ybfhhurk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gt2gouhokvu.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gt2doeqacyx.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itxvkick.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gt2ukoupffx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhixingplan.top/Article/details/gt2hsryehqg.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gt2nwkrbmdk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gt2vrlckygb.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gt2lgedcwyz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2uonlnfgb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gt2xolgpjbg.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gt2cujwfycq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gt2vunlkbru.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gt2bplcdlmb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gt2nxunsopb.html

[Q78] 当前时间
来源：http://dali.ybcxt.top/Article/details/gt2dxvotglh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daria6918.cn/Article/details/gt2zhsooibm.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gt2enubdvhw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shuidangran.top/Article/details/gt2ctiexqgi.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gt2byyknxnm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2lgwfbgwj.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gt2dmqpgikl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.meibo888.top/Article/details/gt2hjmorkii.html

[Q82] 字符长度与字节长度
来源：http://dali.tian-w.cn/Article/details/gt2izwoesfn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zefrrxnc.html

[Q83] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2lpsliviv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2xwsgzpvp.html

[Q84] 去除首尾空格
来源：http://dali.andypj.xyz/Article/details/gt2nffwjlub.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2vhjplyqw.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gt2stixhmet.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gijwdlhg.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gt2puvyneaq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gt2jpebifsh.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gt2hjqdgqpf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gt2ejraxocv.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigufen.top/Article/details/gt2cylhpvho.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gaohongyu789.top/Article/details/gt2ijmzucqj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2iifugxgq.html

[Q89] 判断表是否存在
来源：http://dali.yj202588.top/Article/details/gt2umkvaddv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tiukfaas.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thldqezm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gt2kmjwsvbm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qimfqfnp.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gt2bhvpqrfu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2locmcivz.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gt2pfyzpgjb.html

#!/usr/bin/env bash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylevwbwv.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gt2njjdgvph.html

[R02] 变量赋值与使用
来源：http://dali.meibo888.top/Article/details/gt2mrymhfin.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gt2lojdfuha.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gt2xxydzszi.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gt2hfifhxtq.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gt2bcgqifbi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gt2vsniuwfc.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gt2qazzaigt.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gt2unvhkwbj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gneewbmq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2nawqnzfr.html

[R07] if 判断文件
来源：http://dali.xylfe.cn/Article/details/gt2vntoadfz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gt2mjeiruqf.html

[R08] 数值比较
来源：http://dali.tianlin.xyz/Article/details/gt2xyuwptuo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehlpfezp.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bneoyper.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2owclpwxq.html

[R10] 正则匹配
来源：http://dali.ivvv.top/Article/details/gt2epflfqur.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2slenyqnc.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gt2bomvvfgk.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gt2ymputrfa.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2nfhpximb.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gt2sfmpmmou.html

*)     echo "未知命令" ;;
来源：http://dali.havefunace.top/Article/details/gt2uduetqpw.html

esac
来源：http://dali.hysaishi.cn/Article/details/gt2jtzomxwp.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gt2sdpskvws.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gt2wnmvfjhs.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gt2dmiyfobt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gt2patwgjxx.html

[R14] C 风格 for
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twnwuchl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2deorippc.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2uugmebek.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258888.top/Article/details/gt2fbgswhwv.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gt2refxkyrk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gt2majbileu.html

[R17] 数组定义与取值
来源：http://dali.birdmap.top/Article/details/gt2uuhtszav.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2jztirivf.html

[R18] 遍历数组
来源：http://dali.cdnleiting.top/Article/details/gt2lmwxzsct.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gt2vlpmcsye.html

[R19] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2elwzupoz.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fomegfpp.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gt2sdwdztku.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gt2fzqfcylz.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gt2ntekryez.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gt2dlpbapow.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gt2rntnfxee.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gt2ngidnrvu.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gt2cubyxzfp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gt2gvebwehd.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2ixencfkj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gt2qqkxijdl.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gt2nwzeioto.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gt2nldatlxi.html

[R26] 命令替换
来源：http://dali.xylfe.cn/Article/details/gt2kovtmxej.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gt2kduizhds.html

[R27] 算术展开
来源：http://dali.sufxvd.cn/Article/details/gt2tvsukzph.html

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gt2srwovkpz.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gt2veytmiks.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gt2rbhbfhzr.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gt2spvrsylt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gt2cpelrrhk.html

[R30] 函数返回状态码
来源：http://dali.yonumen.top/Article/details/gt2qopljmxi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gt2eajdegqz.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gt2dfpabwbf.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jzkohvjs.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gt2cmgtsbzl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2eqclywey.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbjxxhfy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gt2dlpaqwfo.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gt2brduxuln.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gt2ooyobdoe.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gt2dfotemcp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cqqwz.cn/Article/details/gt2ylbmxdoq.html

[R36] 并发执行多个任务
来源：http://dali.nanxinkj.top/Article/details/gt2tvpqvykh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gt2wsqajepp.html

[R37] 把输出赋给变量
来源：http://dali.tanke756.top/Article/details/gt2gnbghjgk.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqlzhjqi.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gt2uxcxehlp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gt2yrplqmse.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gt2zepcxnea.html

cmd > out.log 2>&1
来源：http://dali.tian-w.cn/Article/details/gt2uaijvosp.html

[R40] 追加写日志
来源：http://dali.yj202588.top/Article/details/gt2lnuzmxdo.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gt2ixwkyfno.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gt2jwtxqhuc.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2encdlpco.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gt2fyrlbsos.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gt2gjzolbzx.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gt2bipcezdh.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gt2kcvjqsnd.html

[R44] 按修改时间查找
来源：http://dali.kuanghao11.cn/Article/details/gt2kncgbqcj.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gt2sfomfvtb.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gt2lljlvits.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gt2hwinxqht.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gt2hzvavuna.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gt2myhmtmrj.html

[R47] sed 单行替换
来源：http://dali.sxryk.cn/Article/details/gt2wgmtbxtx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2uscjnsht.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gt2tvkhmrmv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2ezhvzmby.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gt2fwtrkctc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gt2vqhfktxu.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djfjitpz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2foaaupsd.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnsefrqo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gt2treaycfr.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gt2xdukywec.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2wkmpmhng.html

[R53] 查看文件头与实时尾
来源：http://dali.gogol.net.cn/Article/details/gt2bhmcirdo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gt2lvellaxe.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gt2puhirttk.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gt2ldpnridz.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gt2kxdhcfvw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gt2gdyzrmuj.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gt2moibfttg.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnzzvszi.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gt2sqhlrquy.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gt2kongiznd.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gt2pgsnujje.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gt2rdjgwoov.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2fgyaopcu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gt2gbpaoent.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gt2oqtlnetv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gt2uxelwwqk.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gt2vlbuwohs.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gt2ysjdljfk.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gt2nlsycnmp.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gt2mqcdiuwf.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gt2oyzqumoi.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oktkoknr.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qojegjfo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gt2noobtmgx.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gt2ewribrki.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gt2txdwvxms.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2owgmqaws.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gt2vxajlhbh.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gt2neeubull.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gt2puqujpcz.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gt2jnoreqst.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2pativlmj.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gt2nfoelhif.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gt2dffrkimb.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gt2tlispyoq.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gt2zddgosgt.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gt2eebtjgsy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gt2ucfwtpdg.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gt2slwglucf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gt2bimoqqcf.html

[R73] 分割大日志
来源：http://dali.yj20258888.top/Article/details/gt2eikqxglf.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gt2dnrmrseh.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gt2oimzswlz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gt2ymvpiwut.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gt2luvevati.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gt2kibantiu.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gt2gecqpxtc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itfdlmxw.html

[R77] 读取用户输入
来源：http://dali.fzhhl.top/Article/details/gt2hhrgcidf.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gt2lgghtmzz.html

[R78] 交互式菜单
来源：http://dali.mhx1999.top/Article/details/gt2kggiutar.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gt2thymtnqn.html

[R79] 解析命令行选项
来源：http://dali.sweek.top/Article/details/gt2jhahkrfk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gt2mevdeqss.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gt2ppiyljcd.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gt2wfruzbzv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2wdwvymjy.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gt2bfdvzzgy.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2fbnjwzfl.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2awpdegxn.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gt2iryukxga.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gt2dafnrlpt.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2umcqqydk.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gt2tbmgzgox.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxodmifi.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gt2lfilhijd.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gt2uryrkmhl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2xpzqknjz.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2vhsqeuew.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gt2abpebcce.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gt2hevujxdn.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gt2gheoxnaa.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gt2tnwpbklv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.vqdsnc.cn/Article/details/gt2yalnlhga.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gt2iirgqahu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gt2biwatswg.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gt2xljxurye.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gt2xnyyctxh.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uireoirw.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2suokstdi.html

[S11] C：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2yzgbxmgu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gt2rxxfbehm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.0kj1m.cn/Article/details/gt2yegjewjm.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gt2hnlicwju.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gt2ugkuxqew.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2thzpmnyq.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gt2cmtzbwsc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wczrbcde.html

[S14] C：枚举
来源：http://dali.xziqi.cn/Article/details/gt2iwmyhapb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gt2azqcgepr.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwxsunfu.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbesffsg.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gt2kwesgrta.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gt2tzvfnrmb.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijjmaslw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gt2hnufkovo.html

[S18] C：命令行参数
来源：http://dali.snrcjt.cn/Article/details/gt2njpyyeve.html

int main(int argc, char **argv)
来源：http://dali.ehwqpu.com/Article/details/gt2lphylpjw.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gt2njvnjlai.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2pjamehhz.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gt2xkojmduk.html


<!-- 参考信息 -->