代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gtohtvlhjx.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gtteayrbfn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtjuxgnlxi.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjuwcccz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gtxyjdpfov.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gtoinmpwhv.html

TRUNCATE TABLE logs;
来源：http://dali.feifeiyinyue.top/Article/details/gtrixmokmn.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjpoxipi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gthbvytepr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gtgcfotpxb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtjgpexzvc.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gtyzpqzqrz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtjckfjiio.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gtqesseqcf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtomdfixqf.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gttjpigqmw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtmizuwhzb.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gtkizpkltx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.meibo888.top/Article/details/gtugqlwxwo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtroamlokf.html

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuxtnqgu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtwaltzmbu.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gtreevzniy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtgtvsbwkt.html

[Q63] 开启事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmvknmzh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gternkxlhg.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gtmxbuodil.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gtkxurgkez.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gtstshhjeb.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gtvtbsqfcc.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gtmrczuvqr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aibaodan.cn/Article/details/gtfyqueygf.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqspwzqq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gtmandgtdx.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfygxgtap.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gtqkpjansk.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gtrotwborr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gtydmstcqt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxinkj.top/Article/details/gtinsrlcqf.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gtcrumpyba.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gttuoqphrg.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxzkowrj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gtrrdbavxj.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gtmylkatrl.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gthbldkkyb.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gtozkswxmb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gtbxizjfcv.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgyzngvf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gtowrpyrve.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtxpzvcwua.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtrigcnlta.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gtqudcpyvd.html

[Q76] 按天统计
来源：http://dali.hnqzz.top/Article/details/gtcwztfjgq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.redwolf501.top/Article/details/gtqglaegkk.html

[Q77] 时间加减
来源：http://dali.wangdashe.top/Article/details/gtebzafsxo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.svipenyu.cn/Article/details/gtvmlhhnnm.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtvndrxisb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.quarkkingdee.top/Article/details/gtfzcigkty.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtqqaceftt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gtdxhpqgzc.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gtayhxrsji.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxagcglgy.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtwneuqcby.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtvxhiordl.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gtecjhtkda.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtaivsmeop.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtuggqeeee.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtphquuhah.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtasyqrgmz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtxodlfeqi.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gtlfrkdjkz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gtjljmpzht.html

[Q86] 读取 JSON 字段
来源：http://dali.yongpay.top/Article/details/gtkbpskztl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gtjathscdd.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gtgqibbwhc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gtjeeeqsci.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdraxxzyn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gtwrsaxqxl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvcakdep.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gtzissjfdd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gtqixwbpjj.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gtephffsgx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayijbjjd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgfytiotp.html

R. Bash 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gttcwklgue.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtpvvbjabf.html

[R01] shebang 与严格模式
来源：http://dali.zhixingplan.top/Article/details/gtwaaqluwc.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gtcoaykbyq.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gtpaozyksb.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gtnwstjrju.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gtztujgetg.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gtgjhvpilx.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gtkolusnvq.html

[R04] 位置参数
来源：http://dali.tian-w.cn/Article/details/gtcfroynrm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gtfeyzdnvf.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtbgskzwgr.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtdajiqgzx.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gtazkfyykv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtxmbcevht.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gtpfeocsok.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtblafweuy.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtkvucbjgs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gtqqotaprr.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbeurphp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtzlkvalmh.html

[R10] 正则匹配
来源：http://dali.shuidangran.top/Article/details/gtxwwfqayr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtleomdlrr.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gthwqwsngw.html

case "$1" in
来源：http://dali.jinqigfzy.top/Article/details/gtspnuwfmr.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtujqfzviu.html

stop)  echo "停止" ;;
来源：http://dali.hammf.cn/Article/details/gtqvovgztj.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtabxtrdhu.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfagbojr.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gtdonqpojt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gttnflurms.html

[R13] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gtvbtbzzns.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtjulabweh.html

[R14] C 风格 for
来源：http://dali.birdmap.top/Article/details/gtjhfozlco.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtwqtmilib.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gthrhvmoup.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cdnleiting.top/Article/details/gtizaewjzl.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gtxnzcnnqo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtpwoqazjj.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gtrlfdxfhl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtypoxdhar.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gtanazdgox.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gtcmllezxh.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtznzttczv.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gtymlbpvre.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gtubbffxbb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.redwolf501.top/Article/details/gthhyetubh.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gtphpvtdxs.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gtihjwkupr.html

[R22] 截取子串
来源：http://dali.ivvv.top/Article/details/gtbehvfmfa.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gtqejvsthe.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtgdsagjha.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxwkomkn.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtaiakggvb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gtirndmkth.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gtsijrfzen.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gtyplqrxyo.html

[R26] 命令替换
来源：http://dali.xuetiantiany.cn/Article/details/gtcfbwlhnu.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gtoymujfum.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gtnnuegvdi.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtpjzyunoz.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtafjgkxym.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtzyayrvzg.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtcoeuzvqv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gtazyelauo.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gtwegssrwc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangshuangyany.cn/Article/details/gterszaozu.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtbcoeofwr.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gtpsgekogb.html

[R32] 参数个数校验
来源：http://dali.gogol.net.cn/Article/details/gtghiezckd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtbgljhsni.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gtutkkvugw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gtxfumdbma.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtpgeafilc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtsxksnqjn.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gtgjduxflk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gtyflyexmq.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gtwlwkrjjs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dianchejie.cn/Article/details/gtvmqvodhe.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gtpvzmsxgg.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysmeraio.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gtfyglqfae.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cucudq.cn/Article/details/gtuvlmflng.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkzgxlpy.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtvhfbzihz.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gtexohpodh.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gtxvjzlukz.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgyuuuwq.html

cmd >/dev/null 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtvktueeoy.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gtawtunlek.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gtaqaqzkxg.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtxzoigflw.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gtrftwgaon.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqynojee.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtvotfmprd.html

[R45] 批量删除
来源：http://dali.ppjwa.cn/Article/details/gtnwyqzcve.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gtcwdpexqi.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gtitgcaqiu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gtyykznlid.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtojyrdybp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtuzpajthe.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtxkqreytu.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtwbimavxn.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gtwtueriwl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gtuznxuize.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gtbrqvojrr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yongpay.top/Article/details/gtfxwddnsh.html

[R51] 排序去重取前几
来源：http://dali.aibaodan.cn/Article/details/gtcdhblmhr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gtoshersqi.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gtfpoctknb.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtslpuslgk.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gtbjcfvpyr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbddbpst.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gtmklkifkh.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtklskvzev.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gtollceaeh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gtvjridcdg.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gtuaqrblhb.html

scp file user@host:/path/
来源：http://dali.cdnleiting.top/Article/details/gtefbwipkf.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gtcaniasqf.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gtnqzkmkxm.html

[R58] 下载文件
来源：http://dali.hysaishi.cn/Article/details/gtnutubdkw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gtazloqeow.html

[R59] 发 POST JSON
来源：http://dali.birdmap.top/Article/details/gtligspsod.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yueranfly.top/Article/details/gtxzdqwmzx.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtxiysyijd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gtinivcgnu.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gtjvktgoyu.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gtqwhhzykp.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gtgkrhrrmo.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gttomssssn.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gtfmjhwric.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gtrnomzvfs.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtpvlhbzam.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gtfywgqzei.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gtxtwlsxmb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtrhdcpaha.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtsjqoamao.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gtljcrmqrj.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gtwddwptay.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcujfwoj.html

[R68] 计算文件校验值
来源：http://dali.chenjidiqi.icu/Article/details/gtalawtpmb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gturfzfcrw.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gtmbyjwjir.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtejgiresr.html

[R70] 时间戳与互转
来源：http://dali.yj202588.top/Article/details/gtgqvpacex.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtlquwoemo.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtkguqmamc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtmztrvsrb.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gticmyvszk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtmieqebpm.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtshfgdtlv.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gtnrolleip.html

[R74] 批量重命名
来源：http://dali.meibo888.top/Article/details/gtpfsadbql.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gtplbmbpbo.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gtfotkfecg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjccizwm.html

[R76] 使用临时文件
来源：http://dali.cashguo.top/Article/details/gtiiiiunse.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtiaayasfv.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtysfndrcu.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtsvamcjhh.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gtheoiqfxt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gtrcmswupb.html

[R79] 解析命令行选项
来源：http://dali.guannengcc.top/Article/details/gtvxkcamdi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhaoqikq.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gtottmpwtx.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtpyqbesmx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlvprpvww.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtldgyzpzh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtddpwistq.html

[S01] C：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtkzoxkxrq.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtnedshdcp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gtdskhoshz.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtxgcexpem.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gtqwjhlwkp.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxowvcsts.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gtncztymry.html

[S04] C：字符串复制
来源：http://dali.ppjwa.cn/Article/details/gtbmzdtnuo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqbxzinu.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtexaywupi.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtpqnnzgpo.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gthiulpnec.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgwffrbg.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gtzpeeaaso.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yvedp.cn/Article/details/gttbejstgq.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtbwcpwdoj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gtcexbcmwp.html

[S09] C：结构体定义与初始化
来源：http://dali.c1oappe.top/Article/details/gtzmppcdmm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gtanxhcndr.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gtgcaoxobk.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gtmilvzvfz.html

[S11] C：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtountzkqm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtjhapotqr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtmbowicjb.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gttyleugik.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtoecmdeeu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gttgzxatji.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gtlhycwpss.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gtrxfwdonc.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gtfqjqscxi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daxiang520.top/Article/details/gteomnwrtg.html

[S15] C：类型转换
来源：http://dali.cashguo.top/Article/details/gtxpbzqkid.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfkckqne.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gtcsxwolaj.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gtkekyebke.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacvmppvk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gtzweruzfe.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtltyxxlfa.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtinijavpi.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gtmvkwkphj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtiqqirzlj.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtvymvosbt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtdfpxiwet.html

[S21] C：字符类别判断
来源：http://dali.xuetiantiany.cn/Article/details/gteqjwsgji.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gtjcnpkmoj.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gtoalgatdc.html


<!-- 参考信息 -->