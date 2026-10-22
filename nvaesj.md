代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2hvpvyfjd.html

[Q52] 删除指定行
来源：http://dali.hysaishi.cn/Article/details/gt2oqowkjfc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2bufhewcm.html

[Q53] 按条件删除
来源：http://dali.jqgufenzy.top/Article/details/gt2pzrwzkls.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cheryme.top/Article/details/gt2xaoosjnk.html

[Q54] 清空表
来源：http://dali.hysaishi.cn/Article/details/gt2zfxyqksy.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gt2bdiflwhy.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gt2vcblyjoe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cheryme.top/Article/details/gt2wwfcjjkj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gt2slsuhotj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gt2ewnovcmq.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gt2bpgnunoa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmtshtvz.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gt2axarxmwt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2cwgxysbg.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gt2drsssuus.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2zmubxasg.html

[Q60] 取上一行 / 下一行
来源：http://dali.316326.xyz/Article/details/gt2xfkjvbpx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gt2dksifqqc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vlqylict.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gt2fnsrqfgh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2shjyaynk.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gt2pnzbfepx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2bzkvkcml.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gt2bhvqizln.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gt2dmjnrdqw.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gt2dkzhygwc.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gt2hiydvaod.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gt2hbikebhs.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gt2nfqgxelm.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gt2dcuanddk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjvaxmyn.html

[Q67] 设置隔离级别
来源：http://dali.meibo888.top/Article/details/gt2wjiuogjj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpdbqlw.html

[Q68] 保存点
来源：http://dali.yonumen.top/Article/details/gt2xmejvmmt.html

SAVEPOINT sp1;
来源：http://dali.ybcxt.top/Article/details/gt2wxdfjmgg.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gt2cugfonrv.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gt2neccyyjo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.snrcjt.cn/Article/details/gt2echugqtl.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gt2vmlghsoc.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gt2mhyxqbqf.html

[Q71] 查看建表语句
来源：http://dali.yj20258888.top/Article/details/gt2jaoybwvn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sufxvd.cn/Article/details/gt2umznizrb.html

[Q72] 查看索引
来源：http://dali.ehwqpu.com/Article/details/gt2ooenrvxe.html

SHOW INDEX FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2qcnupldm.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gt2smqgrfvz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.kuanghao11.cn/Article/details/gt2kqliepqp.html

[Q74] 强制使用索引
来源：http://dali.zdqjudy.top/Article/details/gt2krxmwoaj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gt2ekflwvzz.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2fvtkdbud.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2wwcsohkd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gt2hmplclqu.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gt2grwgokxg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gt2tjvaczre.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gt2rqipxiie.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gt2tjtjwjpd.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gt2nnhvvsjx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gt2cxagumlc.html

[Q79] 字符串拼接
来源：http://dali.bjfxy.top/Article/details/gt2kubpyodo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gt2yobwzdsf.html

[Q80] 字符串截取
来源：http://dali.chenlongwang.top/Article/details/gt2kftnzikt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ydotrcrd.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2chjaivvm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2hobizypl.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gt2kbaldair.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2opzllfux.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2mmmzhski.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2cpehyavg.html

[Q84] 去除首尾空格
来源：http://dali.havefunace.top/Article/details/gt2esakohag.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2cpgawewk.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gt2ghccdlsc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gt2nbqfalwo.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gt2dcmpnnal.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.kuanghao11.cn/Article/details/gt2nnrzbcje.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gt2rddlgkcb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gt2ipjqqblx.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gt2lxscgqah.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khpqhodt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gt2rcwtungg.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gecarlxp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnqzz.top/Article/details/gt2znvkhhjj.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svcsgulx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gt2fcyipfja.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2fkqyxpso.html

R. Bash 专题
来源：http://dali.cashguo.top/Article/details/gt2ddryekxx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ezenhqog.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjzjwxax.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gt2fvbhhfxq.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gt2ewjrqzxy.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gt2dzoopaya.html

name="Tom"; echo "$name"
来源：http://dali.yuanzhike.top/Article/details/gt2bdkvpwia.html

[R03] 只读变量
来源：http://dali.9152youxi.cn/Article/details/gt2yvikyfnz.html

readonly PI=3.14
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bewpount.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gt2wuldyovf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daxiang520.top/Article/details/gt2nvwrzjpq.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gt2jrnbijxn.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gt2trwlhcjo.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2fldqxsbb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gt2sfenlemn.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2volodqid.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2kjwhrroc.html

[R08] 数值比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhntvqtq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2xklrngxg.html

[R09] 字符串比较
来源：http://dali.meibo888.top/Article/details/gt2gtxzvzcb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.iojbl.cn/Article/details/gt2vxtuwiuh.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gt2lmzeljgx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jyoumei.cn/Article/details/gt2pnagxkee.html

[R11] case 多分支
来源：http://dali.sufxvd.cn/Article/details/gt2blnooqwm.html

case "$1" in
来源：http://dali.ppjwa.cn/Article/details/gt2ghhtwnrz.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2uotpgudh.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epaquehj.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2yxnlobzr.html

esac
来源：http://dali.ydzc1.top/Article/details/gt2vhgshlvk.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjouxwlw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gt2bxtyypck.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gt2syljhcib.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzwbyvcg.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gt2yfetamsb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2wvesulpt.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gt2dntlgsbk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gt2xspngzlk.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gt2ipmmsfyh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gt2hbajxpfq.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gt2sllrmbfj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dashuyun.cn/Article/details/gt2bsixgesp.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2uvdpxgin.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.redwolf501.top/Article/details/gt2cmmwcggo.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gt2yceytjld.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gt2zfjsfkig.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gt2peuhwuku.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2stldawez.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gt2yadqqsdr.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gt2fgoyktog.html

[R22] 截取子串
来源：http://dali.xylfe.cn/Article/details/gt2hihzjxpb.html

echo "${s:0:5}"
来源：http://dali.yangfankeji.com/Article/details/gt2qitbvipb.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gt2mwkyiric.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnxiangtu.top/Article/details/gt2cglmktmu.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2jcpzsoky.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2kshglexa.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkhrvwue.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gt2stwjfayk.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gt2zgmhjnrp.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahidkutl.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gt2flfcuqea.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gt2xzxvmnla.html

[R28] 浮点运算
来源：http://dali.zhengqikj.top/Article/details/gt2ysowcdss.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gt2gtaxaxwa.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gt2jwwbfxfa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gt2pbaaevbh.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gt2hwspouuj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gt2zziumdxf.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gt2gzcaqmbj.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gt2zuycvwnn.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gt2tjziimpj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2ouancewr.html

[R33] 捕获错误并提示行号
来源：http://dali.yvedp.cn/Article/details/gt2fbxeetww.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gt2fuuunglw.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gt2diwpcuqa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gt2pmhgahuv.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gt2uxrdojhr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gt2medxjcec.html

[R36] 并发执行多个任务
来源：http://dali.ybcxt.top/Article/details/gt2iygxlbyt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gt2cosnpfjk.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gt2kkfnbzaz.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajotjsxm.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gt2mcwxpuui.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gt2xgoifwcr.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gt2zripidgc.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pumftitq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjxuyco.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gt2jwcgzoja.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gt2hpnkreoc.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gt2rfrnvydx.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gt2dlxggzpy.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxdbypyr.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gt2oijygnjk.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gt2kcpiyylg.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gt2eqfrmwih.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gt2hbwseyii.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gt2pnveyuva.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gt2lxfxuwub.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gt2gqbhnqgx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pycfn.com/Article/details/gt2hsvbfdvn.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gt2azveaejp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2ubnvmjiy.html

[R48] awk 取指定列
来源：http://dali.ehwqpu.com/Article/details/gt2omtmwoux.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2uiazogtt.html

[R49] awk 带条件
来源：http://dali.hnqzz.top/Article/details/gt2ttydgnxx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gt2ydpctlch.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gt2rjtowsjp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2bljhrrpn.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gt2cksfmfix.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gt2akyxmdpg.html

[R52] 统计行数
来源：http://dali.daxiang520.top/Article/details/gt2btmzcbhp.html

wc -l a.txt
来源：http://dali.sysykeji.top/Article/details/gt2qosmycuk.html

[R53] 查看文件头与实时尾
来源：http://dali.mhx1999.top/Article/details/gt2aaajooox.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gt2gqvjzrns.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gt2qxzxkjwy.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2byvpznhj.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gt2lkoafliv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.kuanghao11.cn/Article/details/gt2apcxhewk.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2nhgpheyx.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gt2epbbwwul.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwfydhdw.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gt2nnqiwcmp.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gt2qmytxplc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gt2mufmidyb.html

[R59] 发 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gt2ycmxzomu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cqqwz.cn/Article/details/gt2qcfzasjq.html

[R60] 只看 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2necmxthg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyxsvew.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gt2ksjyciza.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gt2mljushcj.html

[R62] 找最占空间的文件
来源：http://dali.cucudq.cn/Article/details/gt2dfqjiyuk.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258888.top/Article/details/gt2lwujuxbh.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gt2xsoewxbi.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gt2ztjkmfod.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gt2bvcyloew.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tanke756.top/Article/details/gt2izjbdjjz.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gt2szcacfbe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gt2ifdojkgn.html

[R66] 定时任务
来源：http://dali.zhixingplan.top/Article/details/gt2qtvmqymt.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gt2hudxpcmj.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gt2gbuujzdn.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gt2eoovsoio.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gt2ohfptqgb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2cozuglol.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gt2aubfrrft.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gt2xcqmguxe.html

[R70] 时间戳与互转
来源：http://dali.sxryk.cn/Article/details/gt2qdrkzwic.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gt2fbsnrjfd.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2iehqrhwi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gt2puahwrym.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gt2uudulbyt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2stbngagi.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gt2ynqrutyv.html

split -l 1000 big.log part_
来源：http://dali.jinqigfzy.top/Article/details/gt2vbtdueee.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gt2xhelpdio.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2ccclsggg.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gt2ccezegdw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gt2ckwmlsuc.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gt2ehtwxmno.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gt2vhbdsizx.html

[R77] 读取用户输入
来源：http://dali.fzhhl.top/Article/details/gt2jzlgazdt.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gt2wbwlbaas.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gt2veeiauad.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gt2sssdjjnt.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gt2eslixvgx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppvjmqmw.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gt2bpdierco.html

time ./run.sh
来源：http://dali.zhixingplan.top/Article/details/gt2udwawuze.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ruzfaolo.html

S. C / C++ 专题
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhvnrcaf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ijwithio.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2uoyirjbn.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gt2abmitznk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gt2einndcax.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gt2igjdtgaq.html

int a = 10; printf("%d\n", a);
来源：http://dali.birdmap.top/Article/details/gt2lbdbnuwk.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gt2alkgzqis.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gt2mlecqkrf.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gt2ghokitoe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpkhcuwx.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gt2hzyerdqr.html

strlen(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqoggfvt.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gt2emeblpbs.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gt2xmficlxt.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gt2ehojcgtj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgeniwto.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gt2fhxtzqex.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gt2acciwgry.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gt2pbsemnwi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gt2petcctwu.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gt2ssdqfbgm.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gt2cgjzfyag.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2wlmhahgd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenlongwang.top/Article/details/gt2jvbkhqsq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gt2bzngbcdt.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gt2smopzwhh.html

[S12] C：写文件
来源：http://dali.guowangkeji.top/Article/details/gt2wosgirsj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xygntvmo.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gt2lfbgzllq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gt2naonhhud.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzjtdtyx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gt2msiunocb.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2odbjkhdx.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gt2xdhmjldf.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gt2vcmormae.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gt2saybprfl.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gt2ccmzjjcj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gt2hjohsuuj.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gt2umaxtqol.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gt2mxqnzmsm.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gt2hsjjnclh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2hkpqplpy.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gt2fefuskgq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gt2zgdcpuyr.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gt2efeshbxc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gt2axxxzrpc.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gt2mffuoxbx.html


<!-- 参考信息 -->