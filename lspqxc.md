代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tanke756.top/Article/details/gt2lbmjaqgz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2odjvazkg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gt2xpyqqcxc.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gt2hezlvnkh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2gpnvqtwk.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gt2oandpacr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2cogpnjas.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gt2tvrzlzju.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2vamqfnuf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gt2gdvnwoen.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gt2pvcsgaqa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2nezqsvwc.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gt2uftvmreb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2zrlrdkzt.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gt2drvirslg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2tvfhmyhg.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gt2gmiarjzx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gt2wapkqnih.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gt2gkowlcbx.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gt2kjytlsut.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gt2xuzmovxd.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gt2rxpyklhi.html

[Q66] 行锁查询
来源：http://dali.ivvv.top/Article/details/gt2lpziuhlu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gt2rcawfunx.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gt2inlfevex.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gt2xbkqxosy.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gt2sjzatcnk.html

SAVEPOINT sp1;
来源：http://dali.xinyue.icu/Article/details/gt2pdhilohs.html

ROLLBACK TO sp1;
来源：http://dali.birdmap.top/Article/details/gt2fygwnklj.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gt2hktnqvay.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gt2ylawekra.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gt2lurukgps.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gt2dcisflll.html

[Q71] 查看建表语句
来源：http://dali.chenlongwang.top/Article/details/gt2kxfzlswx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gt2nlpojqqh.html

[Q72] 查看索引
来源：http://dali.chenzaomai.com/Article/details/gt2ixzngfil.html

SHOW INDEX FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2rnytybqf.html

[Q73] 查看表状态
来源：http://dali.jianghu66.top/Article/details/gt2cxiqrqoa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2mjtiylgr.html

[Q74] 强制使用索引
来源：http://dali.jinqigfzy.top/Article/details/gt2mdpktajr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ppjwa.cn/Article/details/gt2spxeegpx.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gt2snxkcipf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2lappzdsk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgfzy.top/Article/details/gt2aaexfadj.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gt2dwknsauu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gt2dbkiotkl.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gt2zimafnfk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gt2gxcdjfbb.html

[Q78] 当前时间
来源：http://dali.haohaochexian.top/Article/details/gt2lqhqzwrn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gt2placxmru.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gt2xxbiwudo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gt2cxcfrqpi.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gt2ayyruaxy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2echtckyq.html

[Q81] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gt2yzoepsuj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2xdisfcvv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gt2qbduofyu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2iuzwcylu.html

[Q83] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gt2exkzdbla.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2bimbcxop.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gt2uzdkpcog.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2kaevsqtn.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gt2qlndipbv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.vqdsnc.cn/Article/details/gt2qkopwmrr.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gt2sefjrlkw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gt2lzsycjuk.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxohznry.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gt2nulbulun.html

[Q88] 行转列（条件聚合）
来源：http://dali.iojbl.cn/Article/details/gt2bybdycfc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gt2vpkfnilg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gt2ophnrqqz.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2nwtzefqq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gt2jesfpdmi.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gt2fsusbkev.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gt2dzfgngdy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2qebzowxk.html

R. Bash 专题
来源：http://dali.xinyue.icu/Article/details/gt2fztdgqan.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2pzvhprzq.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gt2lwkjfrjc.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gt2eerluptb.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gt2ferozvbi.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gt2rtrgphfv.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gt2yagtuuia.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gt2qzjkkzgr.html

readonly PI=3.14
来源：http://dali.cheryme.top/Article/details/gt2ntwlglih.html

[R04] 位置参数
来源：http://dali.daxiang520.top/Article/details/gt2pcgabrsl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xziqi.cn/Article/details/gt2syudpbzx.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2sjnqzubu.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gt2itnnzbzz.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gt2ydvtgezv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gt2ktkqtzgg.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gt2mpxyuoxz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gt2zyrctyld.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gt2nwwscfoa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2wgqcapbj.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2ozwzksxj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbecnide.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gt2sdnrbivr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gt2pmnvdwjt.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhaxlxkr.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gt2lgsowkfj.html

start) echo "启动" ;;
来源：http://dali.0kj1m.cn/Article/details/gt2bjndmdvw.html

stop)  echo "停止" ;;
来源：http://dali.dashuyun.cn/Article/details/gt2lmdktfuq.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2wjpenudz.html

esac
来源：http://dali.hammf.cn/Article/details/gt2enwvskzr.html

[R12] for 遍历文件
来源：http://dali.wangdashe.top/Article/details/gt2gknenbah.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gt2fsgwiqda.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gt2gmbxrkqx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gt2abuvjmwf.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gt2czfabnqp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2erdegjpe.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2hcvqiqdx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdwjsfdg.html

[R16] until 等待条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2krlpweld.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sejfggbt.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gt2gacghugs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gt2zelfrbjo.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gt2jvnmgnlm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gt2eueekafl.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gt2qpraatgf.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gt2jmzcwxzi.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gt2vmlrcfpq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gt2aawdppma.html

[R21] 字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2vdcgvamp.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ryjvpxwh.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gt2ubthqwkc.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gt2ielhckxr.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gt2bsorsjaq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ybcxt.top/Article/details/gt2dkpiauwm.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2gtqhkzrm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gogol.net.cn/Article/details/gt2ohadkatw.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gt2zeqslrqe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gt2ytfrwctd.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gt2ykziwaqe.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gt2rvzgezdx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2feuscfvi.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gt2vgzhqhxl.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gt2goniiczw.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gt2wmhhewas.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gt2jutojmgo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gt2icbdksre.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gt2tbhnkpij.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gt2qcfqpepf.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2nnfxazzy.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gt2iteeewbx.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gt2bkvrnqpb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2hsynaxje.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbomtoxx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shzxlz.cn/Article/details/gt2mzbzkaoo.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gt2alrbfupt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gt2ymrtcgrm.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gt2cipgrndi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gt2fowifldo.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gt2siulonjs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gt2fdjrzguj.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gt2hdbqpqsy.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gt2ywmafdqa.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gt2bbcjcczl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gt2iwtocpem.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnkyxgie.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gt2oimnbhvw.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gt2lczeaxev.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gt2hyfdfydr.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gt2nmcuvgzk.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gt2tfurgmxa.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gt2bemdnzvf.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gt2xivvhsun.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gt2jzwjgzeg.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gt2nbojuasz.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gt2jupghrio.html

find . -mtime -7 -type f
来源：http://dali.cucudq.cn/Article/details/gt2oxgapzaf.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gt2yttiadxc.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gt2wycwgsyv.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gt2wlthadyy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gt2fezuuebk.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gt2kxwsnviu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2xlrgrezr.html

[R48] awk 取指定列
来源：http://dali.jqgfzy.top/Article/details/gt2pxqmybgk.html

awk '{print $1, $3}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2xuqjpyxb.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gt2nbhieoke.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhoulong.xyz/Article/details/gt2oiarafbu.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gt2iiiqycjc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dnskbeyc.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gt2ruqkaaui.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gt2bcvsruqo.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gt2vyzudesc.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gt2emwveadi.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gt2tubmovhy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.mhx1999.top/Article/details/gt2ykkclkzs.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gt2qofanfzc.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvqxevof.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gt2akckwlbr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tianlin.xyz/Article/details/gt2cbsqthfy.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2lmjsrysl.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzwosrmt.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gt2kvwyqbwi.html

ssh user@host 'uptime'
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjiultfm.html

[R58] 下载文件
来源：http://dali.birdmap.top/Article/details/gt2cipfnaxb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gt2tafxjscm.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2kmfypdwr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gt2eegwicfh.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2lseqnitm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gt2kspytfsx.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gt2jfsqaakz.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gt2oxphsxaz.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gt2yljpxhxk.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gt2zhyczjvn.html

[R63] 内存与进程
来源：http://dali.tian-w.cn/Article/details/gt2dtekjqyy.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gt2ivespusw.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecideopd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gt2ktopdyng.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gt2rcgwenev.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gt2tvhlonhp.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gt2dvjtdeur.html

crontab -e;  crontab -l
来源：http://dali.cqqwz.cn/Article/details/gt2ffvwjvur.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gt2miexnknh.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gt2lkfugbpx.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gt2zpjzdplr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gt2zjxytmwa.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gt2xhvawpuf.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gt2vczzhvtg.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gt2wcdwsxkc.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gt2hfblzyth.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gt2zubrprsg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gt2kcrzruen.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrhgxdjw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbhlfbch.html

[R73] 分割大日志
来源：http://dali.ybcxt.top/Article/details/gt2eumvinal.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvwibdrl.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gt2whkwofmo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gt2anqfkmdv.html

[R75] 导出环境变量
来源：http://dali.vqdsnc.cn/Article/details/gt2qkoyjaeq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gt2nwlerlcm.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gt2ymnjnaaq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gt2uyklmjue.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqxheixx.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gt2gnpmboww.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gt2shqtjifz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2uoicjxwm.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvdymnvy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gt2umgulupd.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gt2tdtpmkmb.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gt2avjjukhh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2oyvfxwtc.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gt2erntqlub.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlwcmhoe.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2hnafcjtj.html

#include <stdio.h>
来源：http://dali.zhongyouzk.top/Article/details/gt2lxwrmbpx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gt2kifdubcv.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2lxozggsv.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxrmnrxd.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gt2kmzcbbog.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gt2gepmwjua.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gt2mebdosgx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gt2kmnqmxiv.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gt2ymfyncdj.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gt2cqcypocw.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gt2blzmagqx.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gt2vuftwazb.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2ehpqtenm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gt2fxcjopsc.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gt2bqxzhiym.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gt2smkvawrn.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gt2qqwqxqxt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjnatmyd.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gt2yudoslwa.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gt2ajgppfll.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ybtgbneq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gt2gzvnmwzz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpbcpwuq.html

fclose(f);
来源：http://dali.daria6918.cn/Article/details/gt2mmppazyu.html

[S12] C：写文件
来源：http://dali.sweek.top/Article/details/gt2keawkfxf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gt2rryxqaog.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpnklpfn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gt2hfeeimnz.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gt2mgbocfkr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gt2gsbictku.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gt2wvxcmrxb.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hoebanvk.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gt2jayduaji.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gt2grbrbfur.html

[S17] C：安全拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gt2aqoqtfpf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gt2zbwrjmnt.html

[S18] C：命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gt2stbahnje.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gt2yznrehpt.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gt2tnzlxbsb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2lqkhxpkm.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gt2tkeqkzza.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2dowmlfoe.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqjerhkt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gt2aikqcjsj.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gt2qlzuugtp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gt2txiecohf.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gt2zuvphohw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gt2fetabtvh.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gt2onoabxhk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gt2cbhshkmc.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gt2rxgufdjv.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qschlncl.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gt2dtdkbqoy.html


<!-- 参考信息 -->