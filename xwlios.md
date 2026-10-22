代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtglzicnyr.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwywagwk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtufupwrix.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gttqnbjagx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtmyyleuzp.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuxming.cn/Article/details/gttvnbmjaq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gtzzbxegsy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtzluldwtd.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gtjeffkxzb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtsyrwshuv.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gtdgrbgnpy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtbgkeyout.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gtuyunyfwi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guannengcc.top/Article/details/gtzlvbqbwn.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gtqbrxqsyx.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtjnesayhz.html

[Q65] 回滚事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfllaijhc.html

ROLLBACK;
来源：http://dali.svipenyu.cn/Article/details/gtzkwzfbth.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gtklqaruxc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gtltjtsmja.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtvutujwoy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gtqiuvzrms.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gtqjbvcgvd.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gtblmfgatd.html

ROLLBACK TO sp1;
来源：http://dali.ehwqpu.com/Article/details/gtvfyzumkc.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gtrarnxaef.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gtldjvphkf.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gtpsqqgdto.html

ANALYZE TABLE users;
来源：http://dali.mhx1999.top/Article/details/gtexlsdtwt.html

[Q71] 查看建表语句
来源：http://dali.yueranfly.top/Article/details/gtjaabjhhv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gtnscwjomk.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gtjwdjtoyo.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtqzntkmxn.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gtxpqncbqt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtetvsahkz.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gtmhsjcmed.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zycfv.cn/Article/details/gtjxbcjumx.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtezqnmgbx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtjspolfjr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilesvkyj.html

[Q76] 按天统计
来源：http://dali.nwbrower.top/Article/details/gtdlszohnd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gtrydefojg.html

[Q77] 时间加减
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbywmtgt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gtekmdyyvf.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtkgupgajb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gtvcsflcju.html

[Q79] 字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtdbmopodp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gtcppichgi.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtsyjgjpwb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqevvzued.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpkignyu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gtgzausmuf.html

[Q82] 字符长度与字节长度
来源：http://dali.jiagoushi.top/Article/details/gtwjrgxhtk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtoyemjjiz.html

[Q83] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtbvvlhtfd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtfzsdfowy.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtzlstvxwn.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtijhawiwh.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtwnmjujyd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guowangkeji.top/Article/details/gtqmdbtcqx.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gtzvjpkvkm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hongshengwenyu.top/Article/details/gtwedfygwa.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjwcfwpo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtvfjaawbe.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gturatczbi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgfzy.top/Article/details/gtowmntkhx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gtqigibxzc.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gtecglnatv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gtlzfogdsc.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtpfmtyoam.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gtpdyzbrjm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfmpurna.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gtsnqccflv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgelskrtu.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gtjavexgbd.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtoqfbdxon.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gtyictxuor.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gtmgmrifkk.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gtfqpaeqdy.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gtypgafcjw.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gtsxhzdsde.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gtobpojzbu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gtbvzfesuq.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gtrixrfhkz.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gtnlvieuxq.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gtimucgkqf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtnxfmonfy.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gtyzbjmbip.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258.top/Article/details/gtjqquifhi.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gtajncukis.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtmzqencro.html

[R09] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gttcpkqxkw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gtdxndgwxh.html

[R10] 正则匹配
来源：http://dali.ppjwa.cn/Article/details/gtfoufrspf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gthtpvowyc.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtljvwywzw.html

case "$1" in
来源：http://dali.nwbrower.top/Article/details/gtdvwfcnws.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtnmhwfpfb.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtxfltcnay.html

*)     echo "未知命令" ;;
来源：http://dali.zdqjudy.top/Article/details/gtafqdpdqa.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtwgzbyunf.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gttaogpbrv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtuawqacym.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gtmjgvirtd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtjguhkdwr.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtjecipypi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtutrzftcf.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtamzivzas.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gtowkjwvkm.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gtnuhlesqg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtefupzjci.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gtrmvfrzpq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttijytvwz.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gtufpfwlev.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gtjrvlpaop.html

[R19] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsyfkcwi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gtongfgahy.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gttrnjjwjd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nwbrower.top/Article/details/gtalkjobsy.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gtwksdlwfk.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gtzoapwnfl.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtkqjqhxpi.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gtrsuztpaj.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtmbivhjxd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gtuojnknfl.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtoulvboty.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gtuoplzawj.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gtzclaphwl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gtrocfovvt.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gtdmrkfydi.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gtdwsjgnan.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gttumnmtjb.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigufen.top/Article/details/gtdoheheeg.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gtfnneeyrq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtdvwqscdd.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtuheejtuo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gtfpvouvgo.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gtlpcyazsm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gtzlzcozef.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gtsocrvari.html

f() { local x=1; echo "$x"; }
来源：http://dali.dianchejie.cn/Article/details/gtakouetzi.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gtnlypsros.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtxkmipdhb.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gtxteatxml.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258.top/Article/details/gtlvniuzho.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gtrwftevot.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtkyxwugut.html

[R35] 后台执行并等待
来源：http://dali.haohaochexian.top/Article/details/gtcbzhapls.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjivedzbf.html

[R36] 并发执行多个任务
来源：http://dali.jinqigfzy.top/Article/details/gtaszevozx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtkiqcavhs.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gtaaffrwyx.html

files=$(ls -1)
来源：http://dali.aizwys.cn/Article/details/gtprmsdnzk.html

[R38] 管道串联
来源：http://dali.yonumen.top/Article/details/gtfislqlyn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gthjjmigyz.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtgwsifmcq.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtnfhefkhi.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtwldkfkub.html

echo "log" >> out.log
来源：http://dali.pengpengdd.cyou/Article/details/gtlzltnarc.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvqylcft.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtuvufdozl.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gthcanyqmi.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtssqrbelk.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtnvlbaosn.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gtvefopamq.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gtfopkeoeu.html

find . -mtime -7 -type f
来源：http://dali.daxiang520.top/Article/details/gtmbsnzfgl.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gtvccrmkan.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gtwbnltfik.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gtjgttknda.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangtech.top/Article/details/gteqkiqcsu.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gtpaietckv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtnrpjavcb.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gtqarsrgbr.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gtdhvbdhfz.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtgogrunyo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gticntkvyg.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gtrxtauqrt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgzlbojk.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpwkxjew.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gtljxdhvlk.html

[R52] 统计行数
来源：http://dali.316326.xyz/Article/details/gtuxxgrhwk.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtfsrrlxum.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gtvtnhaepl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtlvxurotn.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtomjeqzdc.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gttwatzsbz.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gtznngczil.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gtknisjltc.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gtdolmcenu.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnazvizu.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gtedzdrgtn.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtgpzubtzc.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gtnmjjibrk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtruigyoiy.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtobxltlah.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gtarbjvvjj.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtehfqgpci.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtbastmvxl.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gtapcuhyck.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtfvjhbvyv.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gttpepnqlh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtkvgrorus.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gtlhnhiecu.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gtxiyxkcss.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gtadnxadod.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gtkurihkqb.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gtziputjoi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gtdhnferod.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gtseirqhdo.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gtmqagqxnz.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gtlhplokav.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gtxdyvqnir.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gtqshfonev.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gtnombsamv.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gtkssrzaau.html

head -c 16 /dev/urandom | base64
来源：http://dali.haohaochexian.top/Article/details/gtbmjizaes.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gtupnikwmv.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gtkvxrbhmr.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtwgwcgjzr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gtcosaxmjf.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkcyivwr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gthdqrswrh.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gtpqysnixn.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gtoiqbrcvp.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gtzmureesq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgiujgrh.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtafqlhsxr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtruldfwop.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gtbqnjgvqg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtqsjsuuje.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gtpsjgjndc.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gtopckvkys.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtxzysttjb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gtauttdceh.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtugvopohe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtrpnsyfzg.html

[R80] 查看脚本执行耗时
来源：http://dali.xziqi.cn/Article/details/gtepzmxoyc.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gtthxojqkz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvsctctrb.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gtkyqinizi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkvtrgaxp.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtjlixcpxm.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gtxpzlcbyv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gtaeajuhgf.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gtlxifeeca.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtmbyfoylp.html

[S03] C：读入整数
来源：http://dali.feifeiyinyue.top/Article/details/gtrhhfsikr.html

int x; scanf("%d", &x);
来源：http://dali.xuetiantiany.cn/Article/details/gtwnksiehn.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtwhylghkb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gtywabtwxz.html

[S05] C：字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtwpijurde.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtpdxnhvya.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtazqfbdjy.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gtoyjxmsnm.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtzqqefzcc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gtaasdznvy.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gthmanzmvo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtfcrmqaos.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gtksjpamcf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gtxnxrwtgl.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gtlkvetqqw.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gtcatigizv.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtgahocrbs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtwomtwfpl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fzhhl.top/Article/details/gtyepkmeuc.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gttjyhrucx.html

[S12] C：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtojsgdwty.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtbsegdysl.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gtwzvlqufy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtxskqnh.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gthvjldcvz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gtlclpawuq.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtuvmivxdg.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gtteuaxavy.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gtcnhztlgc.html

x |= (1 << 3);
来源：http://dali.meibo888.top/Article/details/gtqstbjfky.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtzkjoygeg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtpncallhx.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gtembmbesx.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gtrcnmmgmu.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gtlbjgijjc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtbsegfnhq.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gtijgreaum.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtutflnjbe.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gtceacrqce.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gtxawyfvfd.html

[S22] C：字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gttnpioqlm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gtwhgjotch.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gtzwzeoykq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtuefdafwl.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gttxapiasl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gteldrqoek.html

[S25] C：内存拷贝
来源：http://dali.birdmap.top/Article/details/gtiayvlixs.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gtelhcelxw.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gtanadpfdn.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gtnolgubho.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gtiakggbon.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtfqcqkblr.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gtpifqfjcb.html


<!-- 参考信息 -->