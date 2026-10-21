代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtpqgzbvqw.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gtlpvnsrpc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gtfbyelhuo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtawjumyhs.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gtygqhzcst.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtcaunlzyi.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gtzfmvankf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtoopxihym.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gtavxhncgw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cqqwz.cn/Article/details/gtrqumcwkt.html

[Q64] 提交事务
来源：http://dali.haohaochexian.top/Article/details/gtpcbzskdz.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gtitspuipx.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gtvuhkfnel.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gtjmikmnrb.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gtdphnniph.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gtuvwrvcqr.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gtcwbvqiyc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gtnrhivsoz.html

[Q68] 保存点
来源：http://dali.zdqjudy.top/Article/details/gtcwcdqkvb.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gtubpexwua.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gtpphbxbqe.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gthetawtui.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gtalydyuek.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnlctjjh.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gtmjpmjztt.html

[Q71] 查看建表语句
来源：http://dali.yueranfly.top/Article/details/gthqaldiey.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gtaihnbtrb.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gtyqfgdukh.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gthujdjkro.html

[Q73] 查看表状态
来源：http://dali.hnxiangtu.top/Article/details/gtsoywffqe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpsqnzjr.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gthaqcmfrl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gtsflldtkv.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtuhuhnkip.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtcejyclkh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gtehztjitd.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gtreyvowsz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gtdmddvmji.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gttdrwmrvn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gtlcmxkimw.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gthzwbtkwh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gtybdqyzxz.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gthcaczxdf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shuidangran.top/Article/details/gttqvjyjpy.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gtqhkwktcn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtdfnlzatm.html

[Q81] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gtzzapsool.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gtezstbmrp.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gtwqyncamv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtdllxtwvp.html

[Q83] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtfjucgocr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtnkhqthee.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gthvkzxkor.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtukarhspg.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gtizveopnt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsloqzmtn.html

[Q86] 读取 JSON 字段
来源：http://dali.guowangkeji.top/Article/details/gtgvjvbgoq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gtzyuocubz.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtjdyjaceb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gtaqnhpcfh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gttkozbaot.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gtjgswvyyi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gttewdqqiw.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gtfedspwfv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gteqnupaub.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gtpvzdckkk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gtvhvuwgtw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnjqovvjf.html

R. Bash 专题
来源：http://dali.guannengcc.top/Article/details/gtasoxtwrq.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtyajxpgtn.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gtcmfagzag.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gtnocaokds.html

set -euo pipefail
来源：http://dali.jiagoushi.top/Article/details/gtfhvckyea.html

[R02] 变量赋值与使用
来源：http://dali.yongpay.top/Article/details/gtrvxygdbb.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gtfqygensg.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gtjlckcrwn.html

readonly PI=3.14
来源：http://dali.iojbl.cn/Article/details/gtlijxpvqy.html

[R04] 位置参数
来源：http://dali.ydzc1.top/Article/details/gtixnbtkzz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gtmxlihvib.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gtupsnhmqn.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gtvebuxhej.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtbvblbzhv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtotzxtcta.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtnuzympgi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gtjcprhkmd.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gttxltozyn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gtcuxxhrbu.html

[R09] 字符串比较
来源：http://dali.yongpay.top/Article/details/gtgexzssip.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gtbsnwhfqv.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gttmvnqzla.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtbsdhmhuy.html

[R11] case 多分支
来源：http://dali.zhongyouzk.top/Article/details/gtcfaioika.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gthoregshl.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtlfiutypv.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gtxwpiesib.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtxgrrhzvp.html

esac
来源：http://dali.bjfxy.top/Article/details/gtgkexvnvv.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gtflyzxsoz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gtawqagchh.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gttcavfqxg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtyvfohbzw.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gtnceunwal.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtxtsonxdd.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtxumrquou.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gtjhjqeurk.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gtqpfwwapr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtuwpsevtn.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gtanmlxhzj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtajinplat.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gtjmuowsvy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtuaytgayl.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtgjifzfaq.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gtcuzznfcw.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gtorkndfef.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gtfevktqtf.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gtelhjzohi.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gtdarykqif.html

[R22] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtsacfxxda.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gtowgqwdbq.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtzrgciluu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gtwwodryha.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtcxugdkee.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gtaccesjvl.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangshuangyany.cn/Article/details/gtjfusjaod.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gtrpnldoms.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gtqobzrnzb.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gtayukhkoh.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gthfkztmwd.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gtsdcnmumd.html

[R28] 浮点运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgipjcbq.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gtflfbqtug.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtdcphcwit.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuxming.cn/Article/details/gtgptoelrq.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwxlmthc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.quarkkingdee.top/Article/details/gtrihsgkyf.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gtqudhyheq.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gtxnrqaoco.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gtncjrauci.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtbaofvcgq.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtshkynspe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtweuvssbk.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gtlzyklvxm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gttbfzwret.html

[R35] 后台执行并等待
来源：http://dali.tanke756.top/Article/details/gtghwdvaxo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gttckmxlkg.html

[R36] 并发执行多个任务
来源：http://dali.ybcxt.top/Article/details/gtodsfeceu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gtklhuoqhh.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtetpxlrqe.html

files=$(ls -1)
来源：http://dali.tianlin.xyz/Article/details/gtwamydvwn.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtfpfvssxl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhongyouzk.top/Article/details/gtvytgyvzt.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gtoaohragx.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyaylokt.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtovilbgen.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrojeifn.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gtaluasufk.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gtegfhyadv.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gtewuusvfv.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtfhyxwckk.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gtifbfkykf.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gtiflambrt.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gthleoqbic.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gtbwbgeecs.html

[R45] 批量删除
来源：http://dali.cheryme.top/Article/details/gtuccepxpl.html

find . -name "*.tmp" -delete
来源：http://dali.daria6918.cn/Article/details/gtelyllucz.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtilxogneq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gtiphakjqo.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gtuferyvri.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtfevsradm.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtnxsxjxxz.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtypwvhwxb.html

[R49] awk 带条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnelbhhwv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gtecviabwm.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gtwzmhwtiz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtaffqsbbj.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gtxeiagjqv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gtlmiyvrxl.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gtouhpabxd.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gtkyuhmkvf.html

[R53] 查看文件头与实时尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcmmyilh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.andypj.xyz/Article/details/gtllxjczun.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqqvapjh.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtxctlrskz.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gtewhbqsbs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guowangkeji.top/Article/details/gtmlmhgdxa.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gthdsezvaw.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gtumzfpist.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gtdbxbsljn.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gtobgcsokw.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gtptmxhjsf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gtlitimckd.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtjthuogzo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gtpnjqksxd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gttkrrqcvs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gthetznojb.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gtuyqfgkoq.html

df -h;  du -sh *
来源：http://dali.c1oappe.top/Article/details/gtubuwglpe.html

[R62] 找最占空间的文件
来源：http://dali.yj20258.top/Article/details/gtxxzyqmus.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gtsjxtsggg.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gtlterckfj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gtkaceilzr.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtaeoopxmj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtkyhjejgc.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gtyloihabk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbchevevl.html

[R66] 定时任务
来源：http://dali.nanxuanxn.top/Article/details/gtqrpqxcyg.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gtxcdmqsux.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gtmuxgdihf.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gtplwfrqcx.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunyjjpup.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gtplzixmga.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtlcyaythu.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gtayhdwzqc.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gtdqbiqhbf.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gtgwssftdy.html

[R71] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtjnwddaqq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtggwdrntm.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecwkdjew.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtmffklvwu.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gtvqrvegcq.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gtgppnaqef.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gtxrwrkiez.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.redwolf501.top/Article/details/gtgjvkrxcw.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtuygmoyrt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gttwzhwthc.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtkozwrhrm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtiloysrzh.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtqfiwuphr.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gteytbffmy.html

[R78] 交互式菜单
来源：http://dali.haohaochexian.top/Article/details/gtsxlenxju.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gtoznjoqsj.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtvfpdbfwm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gtarnmgiwj.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gtcgbnkxhs.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gtdojjqkdn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnmxbsbzu.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtrdusdltl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gttqbddrvj.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtybjnaolg.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gtzxqdtibj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gtqhfslivw.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtneqpmvsl.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gtcgixkqqm.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gthvkdglld.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtjhgslzhk.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gtjccjlwbq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtokplgvet.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtpsppqarf.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gtgpvzylax.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtscplrcod.html

strcmp(a, b) == 0
来源：http://dali.jlsjyb.cn/Article/details/gtczwctima.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gtizffxdar.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gtmydqzbsj.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtygdktwte.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gtndrcuyxx.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtmmdxcpon.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gtyknexhul.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gtoifjeopa.html

int *p = &a;  *p = 5;
来源：http://dali.xziqi.cn/Article/details/gtnrgqreif.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtcmevusoh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gtylysziaz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gthflnfvio.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtwbijbiwd.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtknbjtnhf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtyjoaiwnl.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gtusehvwva.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtkzofdwfq.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtklardrat.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gtfhoqcycw.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gttilsjyrv.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtqstngbcp.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gtaqhlvivc.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtogrrykie.html

[S17] C：安全拼接字符串
来源：http://dali.tian-w.cn/Article/details/gthxqopzgl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gthccvbgsh.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbifeyuc.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtwydkcoat.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtgdkiigpo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtssgtgaok.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtknlfhdxy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtkuzgvxbe.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gttghmeldq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gtkhqpqypc.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtuioifmsv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.birdmap.top/Article/details/gtlbhkduzn.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtcdlcvoef.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gtpmnynynk.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gtgombslpz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gtutivjoif.html

[S25] C：内存拷贝
来源：http://dali.redwolf501.top/Article/details/gttvmewhgp.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gthbmlmwts.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gthykikglh.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gtfdvfypzs.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gtnsantcee.html

const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtdqcaealp.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gthmscpvuw.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gtwxaxkgvo.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gtiiylndno.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gzhubu.top/Article/details/gtghkzfaua.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtfeyyzclw.html


<!-- 参考信息 -->