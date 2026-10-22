代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2hwletbad.html

[Q60] 取上一行 / 下一行
来源：http://dali.jlsjyb.cn/Article/details/gt2cvrqfmtt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gt2jalofopb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2pemtsrjd.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gt2xplufmws.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2qxvonxmp.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhllbqjf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2xyqwajwl.html

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gt2gygqbcgi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gt2suvzomdd.html

[Q64] 提交事务
来源：http://dali.fzhhl.top/Article/details/gt2idocgqvo.html

COMMIT;
来源：http://dali.shzxlz.cn/Article/details/gt2adyndkyq.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2airrkljj.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gt2icfposwp.html

[Q66] 行锁查询
来源：http://dali.dashuyun.cn/Article/details/gt2vnxjabqh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdwldvje.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gt2pddypcdf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gt2uarblrro.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gt2iiyclxnu.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gt2rzgrxybw.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2aulqlabp.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrnsywnq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nwbrower.top/Article/details/gt2juqinclg.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gt2crvnlmmy.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gt2ssdydsra.html

[Q71] 查看建表语句
来源：http://dali.zhongyouzk.top/Article/details/gt2nzyvvote.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cdnleiting.top/Article/details/gt2mrrlhrfj.html

[Q72] 查看索引
来源：http://dali.birdmap.top/Article/details/gt2twidckyp.html

SHOW INDEX FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2oqpdismy.html

[Q73] 查看表状态
来源：http://dali.guannengcc.top/Article/details/gt2sqoqkkpx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2ruwqyphj.html

[Q74] 强制使用索引
来源：http://dali.hammf.cn/Article/details/gt2ukwwtois.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gt2yykvdwuc.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gt2ockkrxje.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2xfgrveqj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gt2ovktgntb.html

[Q76] 按天统计
来源：http://dali.zhengqikj.top/Article/details/gt2hvjxsgiy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sysykeji.top/Article/details/gt2mkgnbknv.html

[Q77] 时间加减
来源：http://dali.gaohongyu789.top/Article/details/gt2dpixjspo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xziqi.cn/Article/details/gt2kazmbcgd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2szmslzbg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gt2rxivufqt.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gt2qnnxlpzi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gt2wizpmbcf.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gt2oqgweqbu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2apkhcfrn.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gt2pwmdkxct.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gt2xjenwrey.html

[Q82] 字符长度与字节长度
来源：http://dali.xuanzx.com/Article/details/gt2kkukgezf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2lxamaujw.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozdqtwrb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2uaialljm.html

[Q84] 去除首尾空格
来源：http://dali.cheryme.top/Article/details/gt2khcsvsdu.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2vzrgekjl.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gt2sdrelrus.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gt2cwkvyrxp.html

[Q86] 读取 JSON 字段
来源：http://dali.svipenyu.cn/Article/details/gt2kuzhkpsw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gt2xvulshle.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gt2kwekjwss.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gt2rqbbipvx.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxmpyyce.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gt2lhfxoeaw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2hfaycuvd.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2juijrwww.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2rwxghqqt.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gt2hgavkcpf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxrvvrwg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2nrwgbkaf.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gt2gtsfzhxa.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpnlzxdy.html

[R01] shebang 与严格模式
来源：http://dali.shuidangran.top/Article/details/gt2wfeezfdy.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gt2hjerybsl.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gt2droabsbs.html

[R02] 变量赋值与使用
来源：http://dali.yj202588.top/Article/details/gt2iivtjreb.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gt2vfkwucno.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gt2bhsfzckp.html

readonly PI=3.14
来源：http://dali.dashuyun.cn/Article/details/gt2ywnsztqp.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gt2wekoxtsb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gt2ctuqriue.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gt2tqnwhbvx.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wsyxckgi.html

[R06] 判断命令是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2bfshpjtg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gt2iqgyonxl.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gt2wfsdzras.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtexinz.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gt2vkqlvtop.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2weyuoeis.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2mjudpfea.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2xftijhgw.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gt2tjsvojqk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2lxxkksxa.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gt2snpuvxfe.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxrgkhtf.html

start) echo "启动" ;;
来源：http://dali.xylfe.cn/Article/details/gt2pgzpmosr.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gt2vudncsqu.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gt2hbuyhutc.html

esac
来源：http://dali.bjfxy.top/Article/details/gt2ivpclouu.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gt2ytgawdvj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gt2dkqzjuel.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2curpixoz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gt2wcqtmpnr.html

[R14] C 风格 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zipuwnqb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gt2sfomaycu.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2jzrzmcjb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gt2oiurntrv.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gt2khwjrfze.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gt2wepruywl.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gt2tyvqrnrc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2bejxfttl.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gt2qrtredxn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gt2aiasozsq.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gt2ebhjsksg.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gt2mmgswolk.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gt2ncfzfxuf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gt2yhfhnncl.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2ffqmypeu.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gt2rwjllobo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkrsqlc.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ximkfshy.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gt2hoqaywxa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gt2dkgsupkt.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gt2ydcqbfyn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gt2klvzozwg.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gt2gkhqjsgm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gt2ccqpmhcg.html

[R26] 命令替换
来源：http://dali.jyoumei.cn/Article/details/gt2areagxsh.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfbozcev.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gt2varhbrfg.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gt2dosjvzao.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gt2pnfdepkh.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsdjjjri.html

[R29] 定义函数
来源：http://dali.yuxming.cn/Article/details/gt2ciuwicch.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gt2dbbhxujn.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gt2axdwhwex.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gt2qyrqhacr.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gt2ozetjrhf.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gt2iqswvszu.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gt2pdknphcl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gt2jywwsfcg.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gt2yknyahfy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yongpay.top/Article/details/gt2wfzwcebr.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gt2oxggyhpk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gt2wwenpwky.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gt2yxheoarp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gt2skyuypmz.html

[R36] 并发执行多个任务
来源：http://dali.yonumen.top/Article/details/gt2ucihrzor.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dsnmqhwn.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gt2ccizarst.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yuyisgsf.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gt2izoykidr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gt2zwfzmlhn.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gt2uafymeyt.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2eceriytj.html

[R40] 追加写日志
来源：http://dali.aizwys.cn/Article/details/gt2rxfmlutu.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gt2zvxagxfq.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gt2lrdxdtgm.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gt2vfusmuia.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gt2pfeawyey.html

wc -l < a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2bspduxgg.html

[R43] 按名字查找文件
来源：http://dali.quarkkingdee.top/Article/details/gt2kihuaasn.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gt2babbgxpk.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gt2phpmvlju.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2ggxbziof.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gt2cgbqebtd.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gt2zptrbvre.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gt2suylqiyq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gt2bcjodnvo.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gt2hifzaniw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sweek.top/Article/details/gt2ywesykwg.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gt2vkhafqpw.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2bhxruxqm.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gt2xgdeeeit.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2domsxoyg.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gt2dbwmhwtp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2nxkcldfb.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gt2yknrjgjg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gt2dtwpcmih.html

[R52] 统计行数
来源：http://dali.nanxuanxn.top/Article/details/gt2zlbdrkhi.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2kmybiggr.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gt2ialrfwxh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gt2ayudcwyn.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gt2pavfaodk.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gt2dwkidmrq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyirlrh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gt2ignyytnt.html

[R56] 远程拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkmvqxit.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gt2jfonrrow.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gt2wpgjckln.html

ssh user@host 'uptime'
来源：http://dali.hfpthk.cn/Article/details/gt2yzitjpcq.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gt2jnsineiw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gt2bqoctbhs.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2vcarcmol.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gt2hzjvnsod.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gt2tzxeucoo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gt2mzehoajl.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gt2eyxryeqa.html

df -h;  du -sh *
来源：http://dali.sxryk.cn/Article/details/gt2zdpdaxrj.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gt2lclamdpc.html

du -ah . | sort -rh | head -10
来源：http://dali.andypj.xyz/Article/details/gt2zglpwzke.html

[R63] 内存与进程
来源：http://dali.tianlin.xyz/Article/details/gt2hxidhpet.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gt2gbpcxusx.html

[R64] 结束进程
来源：http://dali.cucudq.cn/Article/details/gt2votaytgl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gt2hroaefvm.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gt2nomrvjuv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gt2apfwsqcu.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydapjfnf.html

crontab -e;  crontab -l
来源：http://dali.yuanzhike.top/Article/details/gt2kkccscvo.html

[R67] 生成随机十六进制串
来源：http://dali.sxryk.cn/Article/details/gt2rxvqjprt.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gt2fqnehfmb.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gt2ijcdvizt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2xwwsscyt.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gt2nqqlbkxb.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gt2lcjodisx.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gt2fbfesjmy.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gt2xzpgdxou.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2vvvckijv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gt2nswzrlsh.html

[R72] 等待端口就绪
来源：http://dali.mhx1999.top/Article/details/gt2iuwudjpu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2qatiobln.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gt2komcuyhl.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gt2dldclsju.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gt2obwdvfor.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulxaooho.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gt2atjoilko.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdhacpfe.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gt2wxspiedp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gt2hogevtps.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gt2dmarsfjh.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gt2jjmvbedh.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adlhymij.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cdnleiting.top/Article/details/gt2amglwzah.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnixbjlz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.birdmap.top/Article/details/gt2lzczxeni.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmtaowta.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gt2kjzcwjxl.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2jlvwoiuy.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gt2pubvrhmi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ddzhphmy.html

[S01] C：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2lkeqtcpc.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gt2gzhthjxn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.c1oappe.top/Article/details/gt2ngleorkm.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gt2thmmuudf.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gt2jgkosfdm.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gt2ilwohcuk.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gt2fyxjsbhq.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywfwiydo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzltqvnu.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gt2aqyqnrgk.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gt2xndfgnjp.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2hvkvhkgz.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gt2jexdbmrb.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gt2vbwwngoi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzdouxue.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gt2kfkencmz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gt2miicmycm.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gt2slhpnldv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gt2ohpvqdar.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gt2casovaxt.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gt2ksokgjiy.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bucwcxhw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sufxvd.cn/Article/details/gt2rfmkwktu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gt2pwunguye.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gt2lecdrpwx.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gt2zayfmknp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gt2tjdmgaxg.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydsdjitm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gt2cqejlojx.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvnjoupe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gt2goebxfpy.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gt2csubenvw.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gt2gqgrabfh.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gt2zdutlnep.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2knwnuanc.html

[S17] C：安全拼接字符串
来源：http://dali.guannengcc.top/Article/details/gt2eihzzlci.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyqrtgw.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2smigkgmm.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gt2vkztfdgu.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gt2brqthmqx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2fjxqichj.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gt2xqseqzje.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhzgxfpm.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gt2bfruheii.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gt2fyfjvlzl.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2ogvtskpa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gt2jfzyzmjv.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gt2aovhifgt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gt2bicucjip.html

[S24] C：获取本地时间
来源：http://dali.mhx1999.top/Article/details/gt2pnfsvxcw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gt2uwcsumyn.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gt2iegwspya.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gt2pigakicu.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gt2nxgunqxw.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gt2utumhvrc.html

[S27] C：定义常量
来源：http://dali.mhx1999.top/Article/details/gt2fkfkesoy.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2qwoohyna.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gt2toexvnto.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gt2avcgfevy.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gt2ccwfjwnn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gt2yqrhgrao.html

[S30] C：头文件保护
来源：http://dali.jlsjyb.cn/Article/details/gt2nfuxdwra.html


<!-- 参考信息 -->