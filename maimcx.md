代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gtzklysjnl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtytvgcuct.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtyitiedzr.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gtquaejyps.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtinenqscf.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gtplgknbbh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtnykryzny.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gthrerwkja.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtcbjzkyvg.html

[Q60] 取上一行 / 下一行
来源：http://dali.jlsjyb.cn/Article/details/gtbjeflqyx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gtttsngmiv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlkxqmnu.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gtcwfpuiww.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtpxyevwjb.html

[Q62] 分组占比
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzygxtxom.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtynmgtfur.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtnbxhoarr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gtkueqawbc.html

[Q64] 提交事务
来源：http://dali.daxiang520.top/Article/details/gtrvzhigdw.html

COMMIT;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdqccdxe.html

[Q65] 回滚事务
来源：http://dali.gotoacloud.top/Article/details/gtjolzpfdj.html

ROLLBACK;
来源：http://dali.yonumen.top/Article/details/gttfbwmvyu.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gtntzcuure.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gtcoqttale.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gtesokvjlb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdmwjhdm.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gtsehtofwc.html

SAVEPOINT sp1;
来源：http://dali.cqqwz.cn/Article/details/gtkrbexcbc.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gtcyrwpmxa.html

[Q69] 查看执行计划
来源：http://dali.gaohongyu789.top/Article/details/gtwotwmhrb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gtxobelnhu.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gtcjkfgqhh.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gtprmxdzqr.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gtjjmcgdam.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtpjwbconc.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gttlnzdkcf.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtfjhxmtgp.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gtuymqczkc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gtciiupszr.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gtgiidtppl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gtmgsuciku.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtfohnnywm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.havefunace.top/Article/details/gtuqnundql.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gtwhtbojwv.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtrsjccuox.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzrixldq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gtysdgzrza.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jiagoushi.top/Article/details/gtaudxkcgb.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtbcvpfiab.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtqzjpcvft.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtmyhralgq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gtmhttajvt.html

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gtbhfepiss.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtoxatsgpn.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtplolttrv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtihqbadud.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gthlnanzqy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtkslsoczw.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtikfhwmap.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtnysnrjpj.html

[Q84] 去除首尾空格
来源：http://dali.quarkkingdee.top/Article/details/gtqoqwpaqe.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtjadyfdbo.html

[Q85] 数值取整
来源：http://dali.aizwys.cn/Article/details/gtjvwrnygv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hywenlv.cn/Article/details/gtezaglznq.html

[Q86] 读取 JSON 字段
来源：http://dali.guowangkeji.top/Article/details/gthmczwwhd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtwkhuspjm.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gteuzbkpan.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnqzz.top/Article/details/gtpdtosyom.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gtreyzkrrr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuanzhike.top/Article/details/gtwckrvhnc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gtbqxxtilt.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtqiodbmqj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtudizamur.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gtuididcmf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gtmmjlesag.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtvzdqxoak.html

R. Bash 专题
来源：http://dali.yuanzhike.top/Article/details/gtzbglaghl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkahvswnq.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtuthdddzf.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gtpkivgays.html

set -euo pipefail
来源：http://dali.daxiang520.top/Article/details/gtzodxragc.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gtkiffhcbs.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gtsxxluydt.html

[R03] 只读变量
来源：http://dali.ydzc1.top/Article/details/gtkavewtpp.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gtsgzuxoak.html

[R04] 位置参数
来源：http://dali.tian-w.cn/Article/details/gtyfuvekvu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gtkavdmtxq.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gtfzxeqhsg.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gtlwzhcsbl.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gtavypunov.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtjfkjonhu.html

[R07] if 判断文件
来源：http://dali.tianlin.xyz/Article/details/gtazengtcc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtumjzrxwf.html

[R08] 数值比较
来源：http://dali.pengpengdd.cyou/Article/details/gtenkfsxvb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtgfyvnons.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtxssospjm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gtlfadxikd.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gtxdwslmfk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gtmufabxrp.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtyhudxrtl.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gtfzlszbxk.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gtooklvcbd.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtanthfpjy.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtcajmkjzb.html

esac
来源：http://dali.xylfe.cn/Article/details/gtytysxoid.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gtycvbxond.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gtywnminlo.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gtndmmlwen.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtfgszcfym.html

[R14] C 风格 for
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrojyftd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtwcdfswwk.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gtvlrledea.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnovzxjvb.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gtcieidhei.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtebxkbvqr.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gtobzoafad.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtlzqcwvzh.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gtsmbdzlvd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gtspzzalwr.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gtuzqihlze.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gthshfeirx.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gtgibzchdi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gtiubpzion.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gtklsbdmug.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gtdjqwugnv.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtyjxetrbp.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gtcwqtbymr.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqplgkgr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtfzhchevo.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvbmkbfn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gtzjqydmpd.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gtlgzqhjfz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtolohcmzj.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtyuonyshn.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gtnymximcu.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gtvqigsslu.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gttnkjgfuo.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvbfonay.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gtunlbkfwe.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gtjdwckjgp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtrpnsnmxb.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gtjvqwhwvi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gtompmlaez.html

[R31] 局部变量
来源：http://dali.hysaishi.cn/Article/details/gtgkzgbzqr.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gtghdeqjva.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtxvtamiiz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtsajnkdyu.html

[R33] 捕获错误并提示行号
来源：http://dali.shuidangran.top/Article/details/gtkbhnqhgd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtldzjavgm.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gtpexogyjf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhjqogpf.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gtnrckjghr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gtanrvvows.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gtdnhexriq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gthfjwsvma.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtmnnuowzi.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtqxxzlcqd.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gtgifxjgvi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayfbmfcv.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gtomicfgyf.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtciutihih.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gtrktlljmj.html

echo "log" >> out.log
来源：http://dali.svipenyu.cn/Article/details/gtysexkbbg.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gtlwibojpy.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtrzgvzevd.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsnmledz.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gtmalsfatr.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gtzxmkjzaw.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gtinotdmoi.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gtupsajoyy.html

find . -mtime -7 -type f
来源：http://dali.xinyue.icu/Article/details/gttjjiogfh.html

[R45] 批量删除
来源：http://dali.yuanzhike.top/Article/details/gtaboulwct.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gtniiwgfgk.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gtdiprmxdl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gtoiymystw.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtsjrbgbok.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtygcudjgq.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gtwsgrqypk.html

awk '{print $1, $3}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtulsqdvfz.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtvssmwkwk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gtpporpkzb.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gtfzvpcqbh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gtyuphccys.html

[R51] 排序去重取前几
来源：http://dali.nwbrower.top/Article/details/gtrwhmajvs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gtreemrrzw.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gtigeujawa.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gtmeuczewz.html

[R53] 查看文件头与实时尾
来源：http://dali.gaohongyu789.top/Article/details/gtaekwqnoz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gtwngfsnfq.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gtrtewfzqr.html

diff a.txt b.txt
来源：http://dali.tanke756.top/Article/details/gtokzcxhxz.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gtadboksdn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenlongwang.top/Article/details/gtjrfpqeil.html

[R56] 远程拷贝
来源：http://dali.nanxinkj.top/Article/details/gtqbdejpzr.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gtfozufyfd.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gtveiyevjj.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdidffdkw.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjenpicac.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gtoswcjivs.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtulfvztdg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gtvpngrniq.html

[R60] 只看 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtdfejrgzs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gtviigtcml.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtbzhwpmxw.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gtrsreyshs.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gtlpxjfbuf.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gttolpgvxn.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gtjznespnn.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gtfnpyuhgn.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gtdtcfsrfl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gtimtddetk.html

[R65] 查看端口占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcjunxcg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gtghezoeal.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtajrfhxdr.html

crontab -e;  crontab -l
来源：http://dali.meibo888.top/Article/details/gtbnwrocjh.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtxvpryzav.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gtudtaaxqj.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gtqcrcueuj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gtgciyxzqr.html

[R69] 生成随机密码
来源：http://dali.andypj.xyz/Article/details/gtjibdjqfb.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gthgybusjw.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gtkwjnitep.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gthmnfnnay.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtnljarbuy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yueranfly.top/Article/details/gtqjujverg.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gtzvovpvbn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gtudczsnlu.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gtwexeeewx.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtneqqpzrq.html

[R74] 批量重命名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdpskqdh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gtpnxiaasq.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtiwxsbyvd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gttxcdzill.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gthvivoayd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtwvtdafmv.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gthqwljidk.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gtbmbdbfyb.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtufvcsvjr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gthvltbckt.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gtdrpkhjpx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnxiangtu.top/Article/details/gtktelhmpf.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtotkxgced.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gthqipdddw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqozpysmq.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtdtbqeiur.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxcemhvsy.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gthavrwoaq.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gtgatgduqg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gtjubgvxbm.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gtvidgmidc.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gtojsgubry.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gtilemvqol.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtnzzlkvjx.html

[S04] C：字符串复制
来源：http://dali.zhongyouzk.top/Article/details/gtrmmxkomd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtudtzenrs.html

[S05] C：字符串长度
来源：http://dali.yj20258888.top/Article/details/gtnbczxszn.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtrbafqjgi.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtjndqmdug.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gtkxclrdup.html

[S07] C：数组遍历求和
来源：http://dali.zdqjudy.top/Article/details/gtkuxhpyiq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gtobsyfkba.html

[S08] C：动态内存分配与释放
来源：http://dali.quarkkingdee.top/Article/details/gtagssffzb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gtdrjkgebe.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtuqmhttks.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtnpvbirdc.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gtdmjdgstm.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtmprumbhw.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfaqjkij.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gtqkofhprr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtdgmrcuvt.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtwlpweixm.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gttwsyapxv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gtwedzaqea.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gtmylsczuz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtiuhgbnxs.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtvlieiswn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtivwxecax.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gtylxhftxd.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtrnzhbhap.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gtyufdador.html

x |= (1 << 3);
来源：http://dali.sweek.top/Article/details/gtwmeugxar.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtiosidovm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gtmaslwbnc.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gtqrhttnks.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gtldyiuxbb.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gtmzotardr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtxeqnhrog.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtpjyczyuc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtmdjoqfub.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gtclmydmlh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtjpfvsksg.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtgnxvxiwo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtbxgozxfm.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gteldrwprq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gthlxlrxmn.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtmwjorhkw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gtgfprcmyt.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gtlamnkkwt.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gtlkipjjei.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtgmbojtug.html


<!-- 参考信息 -->