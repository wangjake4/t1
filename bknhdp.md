代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gttbttwuff.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gtxqfbmfpu.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gtpkzffxpt.html

[Q55] 排名（并列占位）
来源：http://dali.guowangkeji.top/Article/details/gtpmgizmhs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtexelgdhf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gtynlsqmjv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtdkdvcjbs.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gtvbyagony.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtdlmlysgn.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gtqdvudjyx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtjhapnlkt.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaixepih.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtiwypvrkh.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gtfeomkrjs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gtizjjjgvz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtxfcqhzan.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtzodovivc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtrpevawma.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gtpethdrjr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtjkldufzf.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gtkzycupwp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gtuddkoloc.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gtehloehzw.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gtfcaaeztg.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gtavveaovj.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gttburessr.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gthrpzqyrv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvggqdous.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gtpbvpfabb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gtqlzfthog.html

[Q68] 保存点
来源：http://dali.zdqjudy.top/Article/details/gtcxlsjhgo.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gtmkldpfxe.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gtwhorsryw.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtdyistztf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gtgmzwutyg.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gtyttpbohl.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtwhkodflk.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gthgosxlci.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.andypj.xyz/Article/details/gtjckkjpjr.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpxdiqpl.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gtvditnipg.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtkfmspxnr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gtszxovqni.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxqqioln.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gthfwdfymp.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtvdpcfpfo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtpeivuiho.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yueranfly.top/Article/details/gtobdalpmk.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gtpprasaaz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.haohaochexian.top/Article/details/gtmjezvhoq.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gtrdwrwtrm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gtmtbbtqpw.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gtyfsnipnf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gttetvqptn.html

[Q79] 字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtcwrlvwpv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gtsselwiqs.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtemsulqof.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gthuhhckii.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtuidtqsur.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtheqttqns.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gtfqvvtjlw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtoduheeth.html

[Q83] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtqkmmhefk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtjqboocas.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gtvvcuvtan.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtlejcyppu.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtxljetnra.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gtcffyqtrh.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtfimfoupd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shzxlz.cn/Article/details/gtvzmpucos.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gtvosbimgj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gtntnwdbir.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gtxpimkbre.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gtllxkptul.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtamldrzbj.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gtyerrvgzw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gthmvbhahm.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtdhzozdar.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gtdfrhcfpu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtupagrnfe.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegwknddy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtcyjkhufm.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtgibmvtbd.html

#!/usr/bin/env bash
来源：http://dali.jyoumei.cn/Article/details/gtdbllsfos.html

set -euo pipefail
来源：http://dali.chenjidiqi.icu/Article/details/gteumlftpl.html

[R02] 变量赋值与使用
来源：http://dali.iojbl.cn/Article/details/gtyoeajaoa.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtvnvkgrde.html

[R03] 只读变量
来源：http://dali.kuanghao11.cn/Article/details/gtblcvymee.html

readonly PI=3.14
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirmbpdae.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtygurobjc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gtxaitfkxv.html

[R05] 参数默认值
来源：http://dali.fengsongda.top/Article/details/gtfuvajrfn.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gtjwlusdua.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtjvtbpysb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gthswnadbl.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gtlbccrnxo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtgbzbgvrq.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gtfqydzibk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gtrqgjwcgj.html

[R09] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtelblokal.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gtqnoviubh.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gtfutohlee.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtdggfjafp.html

[R11] case 多分支
来源：http://dali.tanke756.top/Article/details/gtaawjrunt.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gtqlxwyuyr.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtpvksndyj.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gtzlephoeb.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gtumetojwx.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyaqnoglu.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gtzkjqbcjm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gttvctznyy.html

[R13] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gtfhsvctsp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gthsbxvkth.html

[R14] C 风格 for
来源：http://dali.birdmap.top/Article/details/gtawqyxuco.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnednugnm.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtbrbdzxbq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gttxvipddt.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gtcjzreqzt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gtwazyhnqq.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gtxbyfnjtl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcatzbqme.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtyvojzgws.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gtdphpexra.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtzthvpkyo.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gtcnxtdnoi.html

[R20] 关联数组（字典）
来源：http://dali.chenlongwang.top/Article/details/gtisitwxdg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gtkryqyqqu.html

[R21] 字符串长度
来源：http://dali.zdqjudy.top/Article/details/gttjmpqvca.html

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gtmoaedokk.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtjiykmzed.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gtkmtknatv.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtrohelovz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gtoiadvjxb.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtxrievzwd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgfzy.top/Article/details/gtaxvdqjmx.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gtytmlownd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gtgokwejed.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gtabpnqftv.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gtkppffoqy.html

[R27] 算术展开
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuhjfdov.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gtvkoajtqr.html

[R28] 浮点运算
来源：http://dali.zhixingplan.top/Article/details/gttosmzdoz.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtednfhibk.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtuwzspjvt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtmynlmkxf.html

[R30] 函数返回状态码
来源：http://dali.fzhhl.top/Article/details/gtesqytgty.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gtjofeibsq.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gtxlolpxkz.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtjlaajobg.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtzplqvcck.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtanoatazl.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gtaujleyfw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfillklx.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gthpvfkllf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtsbnodoci.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gtpggunqjs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gttzaqyhmy.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gtgefxtklx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtasklbeuo.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gtsnlucqsn.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtiqbkrkek.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gtrzejuypo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsrseoiu.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gtupjgnepq.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtptczmsll.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gttuvvurez.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtsmlrbyai.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gtpyfaqrxw.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gtgcktcglw.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzopmxnjs.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gtesxvhctq.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtgurmqjdw.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gthrdeyqum.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gtaeumojlm.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtufpwhslt.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gtvcwhwuul.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gtcbkdhovv.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gtvgnrtkjq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ydzc1.top/Article/details/gtrqixcpgq.html

[R47] sed 单行替换
来源：http://dali.fzhhl.top/Article/details/gtoacrbjxu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gtzlodswcn.html

[R48] awk 取指定列
来源：http://dali.tanke756.top/Article/details/gtkpjtmmte.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtfyxqtyfs.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gthhthuzyt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gtxzaxufnv.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gtzvzgyrlp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtoxbqaefu.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gturlkzhrj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gttlxobhtr.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gtykhwimcw.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gtogupycpb.html

[R53] 查看文件头与实时尾
来源：http://dali.hfpthk.cn/Article/details/gtoynledxg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtafdyukxh.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtrbnkwddy.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gtncsqniij.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtexukzgnk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlfpsmrd.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtnhzgdbry.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtufosklof.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtjioducju.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gtuolzhjgl.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gtukseitqd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gttgldsxxe.html

[R59] 发 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtmphjrjyw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gtkxjxnhhx.html

[R60] 只看 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtcgfrzkpf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtuycxpxoi.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gtwyrmhvvb.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gtybcmipes.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtkdaovaox.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gtinbpwdze.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtjqlaunev.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtomzffdlu.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gtxmnjtxsf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gtlggaildt.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gtbbqjakhv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gtngnujqwa.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtkphorioc.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gtjworiqax.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gtcbiegugi.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtpbobzcpe.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhodqafr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtaxmlqzlf.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gteagtvupr.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtghhatrom.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gtzwudvjfb.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtegzhecsk.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gttrcqrqfz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtkbptxaeo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gtrpofuhkw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtkhhvjrxk.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gtabsrnavu.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gtiihkxgcb.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gtnkkdcplz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.mhx1999.top/Article/details/gttdvmoxcq.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gtmcmrtaxh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtopepcjll.html

[R76] 使用临时文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhdvjtjm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtyokcqvqs.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gtjogurzaf.html

read -rp "请输入: " ans
来源：http://dali.nanxinkj.top/Article/details/gtmleozdxx.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtryixeknq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gtqclvdjln.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gtjteyafdf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhongyouzk.top/Article/details/gtfsfvznpo.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gthsbetvdb.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gtwhclhofb.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtzemrooel.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gtpjvljxuw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttsuquwsj.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gtbrysmmgk.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gtahixdfqn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtcuepicde.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtsfsznkur.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gtvajxtkqd.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gtqwgzzmlc.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gtviqxtjhx.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gtflljkomf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gtuwjffqoo.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gtdvoapqzp.html

strlen(s)
来源：http://dali.cqqwz.cn/Article/details/gtwgeclxnv.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtmmngiaos.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtcbadyibd.html

[S07] C：数组遍历求和
来源：http://dali.yuanzhike.top/Article/details/gtbyxfhvle.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cucudq.cn/Article/details/gtvisaheht.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtgcbzfycy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gtpfvhfeow.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gtagiitgtv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtoktznbcz.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtrckihnnx.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtoedxvwjw.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gtnhuksfuo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zdqjudy.top/Article/details/gtfasbaxsz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtxpdahbvh.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtwyzckohe.html

[S12] C：写文件
来源：http://dali.daxiang520.top/Article/details/gtsnpecyuv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gttyrsnkxk.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gtksctknmb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtbhxbvieg.html

[S14] C：枚举
来源：http://dali.zhengqikj.top/Article/details/gtgfzxgruj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtlfbunybu.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkgutgce.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gtorsdgoxu.html

[S16] C：位操作置位
来源：http://dali.haohaochexian.top/Article/details/gtmnrtfmbj.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gtcpwvmixi.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtgldciwef.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gtqrhxykff.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtbnvrwirh.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gtlxbdvwmm.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gtpmftxtgh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtaogzfwwi.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gtearomxmj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtmbeowpnb.html

[S21] C：字符类别判断
来源：http://dali.pycfn.com/Article/details/gtxvwmgosu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gtzqhoraut.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtccudbvum.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gtxxsmedpl.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gtjfivejlg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gtsekddubv.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtgnghumnq.html


<!-- 参考信息 -->