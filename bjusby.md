代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtidrakykc.html

[Q58] 累计求和
来源：http://dali.nanxuanxn.top/Article/details/gtjzlzpchd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtywoewmdb.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtmqncgytx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gthruxugud.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gtqqpoxoyj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cdnleiting.top/Article/details/gttvcziqii.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gtwluplkdx.html

[Q61] 移动平均
来源：http://dali.feifeiyinyue.top/Article/details/gtflvjombb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gttjqrbvkn.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gtghyeldag.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtnwhfptha.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gtqmhskxrb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.meibo888.top/Article/details/gtyjvjhnux.html

[Q64] 提交事务
来源：http://dali.sufxvd.cn/Article/details/gtpfjxmcmo.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gtampxhbnp.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gtzxeyvvcx.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gtjcnpsbmb.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrxbndpn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gtabyzkbmf.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gtnhuflfpq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gtkppeqpmv.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gtmbzhdlfa.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gtwjywhdwx.html

ROLLBACK TO sp1;
来源：http://dali.ybcxt.top/Article/details/gtsttykebe.html

[Q69] 查看执行计划
来源：http://dali.zycfv.cn/Article/details/gtuikhsfyi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gtydejleyw.html

[Q70] 更新统计信息
来源：http://dali.feifeiyinyue.top/Article/details/gtukcbjziv.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtjxxwbeyw.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gtkzkwksrn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cdnleiting.top/Article/details/gtauzuwpse.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gtozdfgwsk.html

SHOW INDEX FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtdcglqmqs.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtemnotdyz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtimtdlhzp.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gtmlnhdpfk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gtnambpnit.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtkunwvbku.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtnluqgqsk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gtlyxbidwq.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpipzpni.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gtpdnzljyc.html

[Q77] 时间加减
来源：http://dali.gaohongyu789.top/Article/details/gtbmpqtqbr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gttgkqtedz.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmjrlozz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gtudjykjez.html

[Q79] 字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtgdkolyvo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gtjadvmfeu.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gtxvmdkpgc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtlfhhwhcy.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtgopwefah.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gteqgpvlrs.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gtucwhscvb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gteymjchdw.html

[Q83] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuwgmccb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtogjqcjqp.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gtvxxkztor.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtcegwywla.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gtnjhfmdph.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hywenlv.cn/Article/details/gtdrbcidjv.html

[Q86] 读取 JSON 字段
来源：http://dali.yuxming.cn/Article/details/gtxulcngog.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gtbcpjjyim.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtqtljegmk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yangfankeji.com/Article/details/gtpjrpdihk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gttznkvejo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.redwolf501.top/Article/details/gtnznqnsck.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gtacdeiqvr.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gtzjiafrbq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnqzz.top/Article/details/gtuzdimxak.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtunuvsrlj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtmdvornli.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdgzsvwu.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gtowfyspss.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtakefqgvc.html

[R01] shebang 与严格模式
来源：http://dali.tianlin.xyz/Article/details/gtnlyogbhi.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtjcsghhkw.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssswkpst.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gtlwdelrfc.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gttornknnt.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gtwcwarjdh.html

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gtadijebpk.html

[R04] 位置参数
来源：http://dali.daria6918.cn/Article/details/gtpqmbpieo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtwvnkibsz.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gtiycozuht.html

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gtocdzmofm.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gtjgvxsxlp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtzaaoewhv.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gtzkwdnngw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.svipenyu.cn/Article/details/gtrrcuiicc.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gtyuzfczzm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtdrjngjez.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gtsskdpbby.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gtrqjplkea.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtriztnjua.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtvzskyxop.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gtiamzmemp.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gtreagnbeo.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gtzqplqntb.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gtfwtsdkpw.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gttufzfzog.html

esac
来源：http://dali.dashuyun.cn/Article/details/gtkroplaak.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gtxocnnhoj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gtsrkatsyz.html

[R13] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gttjdtdugi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtlowfeaqo.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gtqsfggush.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtxmpnamlg.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtmhhxhxox.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gtaijquwes.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmywotnk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtntlkjijl.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtmezfnpat.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtohrhjtty.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gtitnyazaz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.9152youxi.cn/Article/details/gtxcdktatx.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtcfviekpj.html

echo "${#arr[@]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtrjggfnmr.html

[R20] 关联数组（字典）
来源：http://dali.yanxiufei.cn/Article/details/gtqsvtctsy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtcbkhuqjs.html

[R21] 字符串长度
来源：http://dali.aizwys.cn/Article/details/gthyngrkqk.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gtizpltnjt.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtngxapbes.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gtmtegdleq.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtehqiehlt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtyumgubrp.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtxlvdjhdu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gthusjfjdt.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gtyttwprvj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gtwuumhcre.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylhzepse.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gtrnrpxxld.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gtpkfrmwmq.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gtiuhzyhml.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gtiowcfqnu.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtvtodpoma.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtktzadcex.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gtwxftvxcc.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gtjqokxncf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gtjjmhslpi.html

[R31] 局部变量
来源：http://dali.9152youxi.cn/Article/details/gtzgarqwni.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gtmdtomydf.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gtxpkeybvx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtpzmbykge.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gturgpktpx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgufenzy.top/Article/details/gtmntdhmsc.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gtndxacgwh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtawwxmqbc.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gttbyihsrn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtfovpezhl.html

[R36] 并发执行多个任务
来源：http://dali.havefunace.top/Article/details/gtlbgobbwz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gtyopnizjo.html

[R37] 把输出赋给变量
来源：http://dali.zhengqikj.top/Article/details/gteugnvaqr.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gttkbqtywh.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gtuytonixs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtynisiivu.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtncepqgoq.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtzzcotfav.html

[R40] 追加写日志
来源：http://dali.aizwys.cn/Article/details/gtgztflhne.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gtdiskbjqq.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gtnhbbnykb.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtvvnhlhfq.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gtgryenxxn.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gtujgjxfui.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtouxgfsbm.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gtsksgyveu.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gtvveeiasm.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gtxzuvdjzw.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gttcxdebtm.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gtaxfpsyhz.html

[R46] 递归替换文件内容
来源：http://dali.jinqigfzy.top/Article/details/gtojjitcpl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gtiwqpmgiq.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gtqyxqocgz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtcvncvsou.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gtwxqevntn.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtolkywjgg.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtddloaced.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gtsinpcbyo.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gtgeaqkhwk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gttbhgrvpy.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqfpbrly.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtnbtydojd.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gttwetnlch.html

wc -l a.txt
来源：http://dali.hywenlv.cn/Article/details/gtdzxlejyh.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gtiaccsgow.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtxxioalsp.html

[R54] 比较两个文件
来源：http://dali.jianghu66.top/Article/details/gtxafcnvkq.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gtehoposge.html

[R55] 压缩与解压
来源：http://dali.vqdsnc.cn/Article/details/gtqouqvyal.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gtxwnkvmmg.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtfzbmagsi.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraehpspm.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gtwctnfhwu.html

ssh user@host 'uptime'
来源：http://dali.cashguo.top/Article/details/gtqfofccpi.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gtmdacmdpv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gtqwmtbeye.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtwrhigojl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gtozhodnrv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtaifuobct.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gtymhfxvuk.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtcxiqpzqs.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gttjnduufs.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gtudrocufo.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekfinupf.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gtwoptupxk.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gttsnsnyoz.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gtebiqkmww.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtybqsooah.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvctdevk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmpeumoy.html

[R66] 定时任务
来源：http://dali.mhx1999.top/Article/details/gtssmhxlvn.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gtmuxiijoe.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gtyuxhsdym.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gtzrjfgrch.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtoepmdosy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtsitweceu.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gtrpweskrp.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gthhwntplj.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gtckgvkhij.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgytnxtnf.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtaghhrpef.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sufxvd.cn/Article/details/gtithzbcaj.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gttoeadnxh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxonxvif.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtgxsrgjtn.html

split -l 1000 big.log part_
来源：http://dali.316326.xyz/Article/details/gtcnqexiio.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gtnsaurvvc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gtbeybgmbs.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtiwopwpbu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gtigaimihc.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gtweeotixl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gttlogsred.html

[R77] 读取用户输入
来源：http://dali.daxiang520.top/Article/details/gtkezbkopt.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtxnlghfad.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gtaxiwxpfh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtmfsrnrke.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gtsfozlita.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gtnugmrirp.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvapyqxz.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtsqqfkqjq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzziaaxdd.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjketzvm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtajqkcgzt.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtgarjxpdr.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtxugogrov.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gtvcevefua.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gttnvrayxi.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gtjoyoplqt.html

[S03] C：读入整数
来源：http://dali.yanxiufei.cn/Article/details/gtjzksttsa.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gtuuqoorct.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gtjrdjmanf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gtddwerepd.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtoccxoexn.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gtitqjvksx.html

[S06] C：字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtflgcozjq.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gtulavqjob.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gtsrqkbcgi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gttpikzctu.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gtiboulzsz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gtqmlnrofo.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcskksgq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtczvgrllt.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gthcxebvcg.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gtmangzuwr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtmilkqwxh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtkfkbqygr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtlayparxw.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtbfbmjqrs.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gttcytmvbt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtpuvcsozl.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gtqlgsljpb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gtvyxhlutj.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gtunubmobj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtmwxpkzez.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gtowihqfny.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gtlywdlopz.html

[S16] C：位操作置位
来源：http://dali.jiagoushi.top/Article/details/gtegtyxywr.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhlmiyfd.html

[S17] C：安全拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtjpkarcoh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gtpqgigymv.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtqrclgpjl.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gtzakiuznb.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gtqhxrnknd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtlfaamdan.html

[S20] C：二分查找
来源：http://dali.sweek.top/Article/details/gtglolorps.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gthymcnrdo.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtpphasinx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gtbnjbbtud.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gtjnvqpeoy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtkujdqfgz.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gtfmylxdpx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gtsmbuedlp.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gtbdmatbzj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gtfvzhddjs.html

[S25] C：内存拷贝
来源：http://dali.xylfe.cn/Article/details/gtixwhhfjr.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtwkzrkqoa.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gtsyottxri.html

memset(a, 0, sizeof a);
来源：http://dali.zhoulong.xyz/Article/details/gtvwwglzcs.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gtefkzqorc.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtjvxmlfgn.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gtontwlzvr.html


<!-- 参考信息 -->