代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gt2wqqeskmj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gt2opjpuvdn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gt2cjtvedwn.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gt2ridvgban.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2mjjhlpll.html

[Q58] 累计求和
来源：http://dali.zhongyouzk.top/Article/details/gt2zxisuzoy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2dutryjvp.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gt2mcpiippm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2fonpgkhr.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gt2yrdapkvi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhgkaido.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozobsgev.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gt2mjvpogyy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2ohbernmf.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gt2feogvzam.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgkrebqz.html

[Q63] 开启事务
来源：http://dali.jyoumei.cn/Article/details/gt2dvvjxtdt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gt2xfzdatxw.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gt2xegyegvz.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgrsyxqd.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gt2citwcvdc.html

ROLLBACK;
来源：http://dali.tanke756.top/Article/details/gt2oxnvedxy.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gt2mbheicnb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gt2lmjmoocu.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gt2dikblpij.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gt2pkjzgfzy.html

[Q68] 保存点
来源：http://dali.birdmap.top/Article/details/gt2nubwzjrs.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfugagwn.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gt2yrcedeyk.html

[Q69] 查看执行计划
来源：http://dali.aizwys.cn/Article/details/gt2wbgpbpmh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gt2xzmgxkos.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gt2mitahfpb.html

ANALYZE TABLE users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shzxxvts.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gt2twvardxi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangdashe.top/Article/details/gt2tesogmif.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gt2tenqxuce.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gt2xuecoiwe.html

[Q73] 查看表状态
来源：http://dali.cucudq.cn/Article/details/gt2kbyqzlgo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gt2uiycdpih.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gt2fcgojwlj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gt2dgdtowko.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gt2lsjdncgs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2notexptl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqjseuju.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gt2vosfbzoq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gt2kekomvat.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gt2ejgjnllw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gt2xejpfjjf.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2cztddnyk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gt2tfhjjhjq.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdykuaqc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhiwuduotai.top/Article/details/gt2djcpqzjp.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2anjpenky.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2ecnffdgz.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gt2jjwvyqfl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2tjhhrghk.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gt2nmserdeh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwimkvtu.html

[Q83] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gt2zdgsjdzg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2deyhvwoj.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gt2igcduqjz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2azserqad.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gt2pjcpnkii.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gt2deofporu.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gt2bptktywc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gt2qufunowe.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gt2iuodjkbu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gt2pniuqijy.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gt2qnxwxtob.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gt2vmozvcbr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2ndcixkmm.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gt2egvkhovk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gt2ehqpvqfn.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gt2pxqzitjl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gt2hlekkznp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2mhbdslxl.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gt2fcdawygl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2labvqgsd.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gt2aciijnml.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gt2pxvwlwyd.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gt2rzcfxkwg.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gt2isphcnek.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncvvpmwc.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2mahmkrxu.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gt2hroebmdy.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gt2uxaxuiqr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gt2finaryfc.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gt2kurvavad.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gt2iogdieqx.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gt2mrxnefgz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gt2ccfdpqsq.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gt2taozdpio.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gt2azdsxwhq.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gt2hercjwkn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gt2ownvlfnu.html

[R09] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gt2haanmiau.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gt2upklmurc.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gt2cozliyvt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gt2obsnxbal.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gt2qtzuvhzp.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gt2jjcbikci.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfuaipwm.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gt2wbywhhcf.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2ujoezwjb.html

esac
来源：http://dali.guowangkeji.top/Article/details/gt2ngczikpa.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gt2pniatyrh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2jrzwljiz.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gt2szxhoath.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2tlmdpglz.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gt2ngqhyagf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gt2tfvrmlon.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2phipxsht.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2vmbkaoga.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gt2ozwhayzr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gt2vgpmnkrz.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dudysers.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpahbahn.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gt2anykmpcp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gt2utlfksck.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gt2xysxnycj.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gt2qnvvhkue.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gt2gzbgkqko.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.c1oappe.top/Article/details/gt2londhxof.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2ndixyykp.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gt2zqnjtlfe.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gt2sxcdwdcs.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gt2mpmljjcq.html

[R23] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gt2exffultw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugrwijbk.html

[R24] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iloeeqxc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gt2cmeojlcf.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gt2fspbttij.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gt2qavolemg.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gt2svfxegqq.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nadonzqo.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rczrmqni.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkyckrsa.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2ihiibzxx.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gt2lmawjdbq.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2nszegaax.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfuefich.html

[R30] 函数返回状态码
来源：http://dali.zhongyouzk.top/Article/details/gt2ikzzsrli.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnthfqy.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gt2smpqitxy.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gt2gofleqej.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkrxkksp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gt2upaeyqsh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gt2chrywfew.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gt2qxayhcof.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gt2njvmlckw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gt2pttuwonm.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gt2rjqwmvmp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gt2ykqrxght.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkkdhhtd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gt2syfhomoy.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gt2qfuhlpsq.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gt2rxypjoqz.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gt2godpukfs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gt2qyfaxalb.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gt2bkhsuwhy.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2cvmlhwrn.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmephosy.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gidrrzaa.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gt2xvbbuccr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfetafx.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gt2gyrmpzhb.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pulybeus.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gt2lkczoqmt.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gt2tsopnuit.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gt2ehoiqnaz.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gt2qtvxmdbu.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gt2trulwfia.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gt2tjzgzeeb.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gt2ivvovzea.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gt2kddjbmst.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gt2juavmqiq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2fzjtdezd.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oaydtiyn.html

awk '{print $1, $3}' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2pumysndj.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gt2pyyjqlpi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gt2ocfrrbyu.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gt2lepwouuv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2tddtmcsr.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gt2dfimxejn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gt2bbszfddr.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gt2oomluiqc.html

wc -l a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2mosdljsd.html

[R53] 查看文件头与实时尾
来源：http://dali.cdnleiting.top/Article/details/gt2ucmoiwfz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gt2edcnbzkq.html

[R54] 比较两个文件
来源：http://dali.havefunace.top/Article/details/gt2feutyfrl.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gt2jswxylhx.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gt2cpiryunv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenlongwang.top/Article/details/gt2vvlxovjv.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2urkfvacg.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tvspmqle.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddpehoqs.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gt2ryryukgh.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsmtkcci.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gt2ttlnbuvu.html

[R59] 发 POST JSON
来源：http://dali.xziqi.cn/Article/details/gt2vleswuvj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tokfeygp.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2yolqbgna.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj202588.top/Article/details/gt2gzkukwiq.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbvuiyif.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gt2vqznkrdg.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gt2jwxbrtyy.html

du -ah . | sort -rh | head -10
来源：http://dali.hnqzz.top/Article/details/gt2zwppsryv.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gt2wfzqjxqa.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gt2qvrzznqw.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gt2jhnsrfsm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gt2shicmucp.html

[R65] 查看端口占用
来源：http://dali.yanxiufei.cn/Article/details/gt2hoxbcvja.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydkqtlre.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gt2npeerzqe.html

crontab -e;  crontab -l
来源：http://dali.xuanzx.com/Article/details/gt2rlllcncr.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zunegwcw.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gt2horjxuub.html

[R68] 计算文件校验值
来源：http://dali.andypj.xyz/Article/details/gt2ajdownbq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gt2zfkqjhpp.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gt2vzqnhdls.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gt2qrvmehue.html

[R70] 时间戳与互转
来源：http://dali.ydzc1.top/Article/details/gt2pbugpfge.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gt2pwsqzexk.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2nohlvjka.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gt2ntuvobrd.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gt2sgtlygnm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2jpyzwphn.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gt2qnkwcqit.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gt2kgzresyk.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gt2lotcjgch.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yongpay.top/Article/details/gt2djqatsvf.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gezcizdz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gt2kssxmlgr.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gt2hjmhnjhu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gt2ozbluerz.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gt2kacbsatw.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gt2xzvswipb.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gt2vtfefdbc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gt2dmgetffa.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bioeupnx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2dovnxhlv.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gt2pnvbenag.html

time ./run.sh
来源：http://dali.shuidangran.top/Article/details/gt2qkqlxrsz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2qlpdvnxi.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2riluoafe.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2wawevmxt.html

[S01] C：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odtdljur.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gt2yynevrxo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gt2oozuizfk.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2pphpueiz.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gt2zuqajsas.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gt2gvwdfbys.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gt2mpftlcmz.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gt2yxljiqdv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gt2hytnrroc.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gt2cvuovlfb.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gt2glhqothq.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2bvhtjrqe.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gt2qzbeykpp.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gt2xieecjev.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gt2xhainvaq.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gt2nrtysfsd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gt2ynnyodgp.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gt2gwtmfvap.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpjilcbe.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gt2uguwpqew.html

int *p = &a;  *p = 5;
来源：http://dali.nanxuanxn.top/Article/details/gt2wpsjkbyu.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pcbvbrhm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gt2iakoekhg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obtmkytx.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2mrocdmld.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzppybjb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gt2rqqndcop.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gt2dpunzffn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gt2xczbwoml.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gt2ajnlkgku.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gt2snftbchp.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gt2klfjaoqu.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gt2vhohvnyq.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gt2fklqgpwk.html

x |= (1 << 3);
来源：http://dali.guowangkeji.top/Article/details/gt2wcattbeh.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2piprkcfe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gt2xseaoylj.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gt2mclqxvtu.html

int main(int argc, char **argv)
来源：http://dali.yvedp.cn/Article/details/gt2bdpiqrae.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gt2ivjsttil.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2zfmijkit.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gt2yuyorcxy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2dtieecye.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gt2qqnjpypj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gt2nvtmvojv.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uthhhnwr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gt2qvhugeid.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gt2cmkvdivv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gt2hnpmussn.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gt2mriyrxys.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gt2dijeefke.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gt2ndkgkzlf.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gt2wbnwieco.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gt2qicamvem.html


<!-- 参考信息 -->