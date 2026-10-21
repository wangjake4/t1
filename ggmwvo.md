代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtzxhfwbes.html

[Q58] 累计求和
来源：http://dali.hnxiangtu.top/Article/details/gtemmxkbsu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gttarwimtb.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtwohzxsxz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gthxhrrpzy.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gtfyqnmbhz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gtblupzrsu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtzrnqjmfa.html

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gtbnabpwue.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gthbruteem.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtwhrijvrv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtyckkhmwn.html

[Q63] 开启事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevsxznte.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gtqxfgmokp.html

[Q64] 提交事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswaoqlfm.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gtpfyhfkko.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gtkqciyhmc.html

ROLLBACK;
来源：http://dali.xziqi.cn/Article/details/gtctjqspio.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gtujgfihxd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtvpbaqsgo.html

[Q67] 设置隔离级别
来源：http://dali.chenjidiqi.icu/Article/details/gtmykxiwoq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gtmhuwvzqd.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gtjijbmnww.html

SAVEPOINT sp1;
来源：http://dali.zdqjudy.top/Article/details/gtxsqedekd.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gtveruyxxl.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gtxnozmltf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gtxeivntee.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gtsldgaxji.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gtfuertncj.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gttkwoaoau.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gtzxlsepic.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtbaomthmu.html

SHOW INDEX FROM users;
来源：http://dali.hnqzz.top/Article/details/gtynzqarxc.html

[Q73] 查看表状态
来源：http://dali.tian-w.cn/Article/details/gtmektddqc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gthbqyxowx.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gtpvuybhyr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtlyapzizm.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtgfnzhcuw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtgvocvrmu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtfglvdzot.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gtuqjqrfhx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtvflljpmk.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gtkamdrurf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtcgmkmdaq.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gtgzwxrorf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gtmgtijpas.html

[Q79] 字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtrlikpbxp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gtnkpelrgw.html

[Q80] 字符串截取
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkfbnepk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtaopublro.html

[Q81] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gtbhkzxmky.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtigyybyuo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gtemmwoztz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtvfzaciel.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpunncpwd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtaphjjjkm.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gtuwhkwiqq.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtbnjgcnjy.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gtwggxvdri.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gturxqltvf.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gtsqouovgv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gthhhpcxfe.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbzhrigz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gttcedmxaz.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gthmaeivnf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gtzsmuajhe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gtzuhbfuao.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtufeqobof.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gtfajvsqud.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gtxjlplaok.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gtelguqmon.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtekaekmuh.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqagnfjus.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkaynfvcv.html

[R01] shebang 与严格模式
来源：http://dali.nanxuanxn.top/Article/details/gtwnqnctwr.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gtgxhkeywg.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtndxnedtu.html

[R02] 变量赋值与使用
来源：http://dali.xinyue.icu/Article/details/gtxhvsnntl.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gtajotcbay.html

[R03] 只读变量
来源：http://dali.daria6918.cn/Article/details/gtskcwubqp.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtvfuwtizk.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gtlqbogdpg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtoabudicd.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gtktnbdcko.html

name="${1:-default}"
来源：http://dali.jqgufenzy.top/Article/details/gteayfthgj.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtzzgctzhy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtocwzrlqr.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gthnwakrzt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtomflveab.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gtntirpiwf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtqpjlxxdl.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtvoutdnsa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gtfiezgwjz.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gtbxfonzhl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hywenlv.cn/Article/details/gtdfulemxl.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gtdlpmwybl.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtanhbjexa.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtatpvptlk.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gtrcmncdat.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gthkyusexf.html

esac
来源：http://dali.sxryk.cn/Article/details/gtthwhuvtu.html

[R12] for 遍历文件
来源：http://dali.cucudq.cn/Article/details/gtwulmhfdc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtkdefqsav.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtoaxqaiht.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtqouzosaf.html

[R14] C 风格 for
来源：http://dali.pengpengdd.cyou/Article/details/gtcczhcecd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtecphtwpv.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtuqhgswrp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuiwtlobi.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gtswuyaeig.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtjxjhndzb.html

[R17] 数组定义与取值
来源：http://dali.vqdsnc.cn/Article/details/gtcsvhzpjk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gtrbepculy.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gtdorcozzn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuanzx.com/Article/details/gtexypgmfo.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtxkkhfghe.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gtufokjsln.html

[R20] 关联数组（字典）
来源：http://dali.yj202588.top/Article/details/gthbvvvrtl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gtbvcxqahp.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gtcnofxpku.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gtfzyfccit.html

[R22] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtnztcaehw.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gtnrkmfbnm.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtbiziwwrx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gtkizktryx.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhstsddc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ehwqpu.com/Article/details/gtffhwogus.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gtztgtllhd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gtmagblweh.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gtjlrbniim.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtgimkgphv.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gtnjzvveev.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gtcdxrqwvu.html

[R28] 浮点运算
来源：http://dali.jinqigufen.top/Article/details/gtkishapva.html

echo "scale=2; 10/3" | bc
来源：http://dali.gogol.net.cn/Article/details/gtcbmxvpxv.html

[R29] 定义函数
来源：http://dali.yueranfly.top/Article/details/gtnfdqdfrf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.vqdsnc.cn/Article/details/gtertjhluf.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtyrlhtjiv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdjwcpzh.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtgvwhfzrp.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtzmnidxxq.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gtlgzgidom.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtdmcwgsrd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gttfhtjmpj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258.top/Article/details/gtyzweyqvc.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtrqmorrmg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtvplzgbsm.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gtqbdoooix.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gtwnzsibou.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gtnodywjnc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gtxgbhpvkz.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtarhpbasu.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gtztwxpjqu.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gtpxryvbhl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gtohjlfgvc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gtkgfgkttm.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gtdpanoyya.html

[R40] 追加写日志
来源：http://dali.sysykeji.top/Article/details/gtrlvpsrmw.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtkejmerut.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvkojaaa.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gtslybobvk.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gtgqhlmtgd.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtarjnguyn.html

[R43] 按名字查找文件
来源：http://dali.jianghu66.top/Article/details/gtspnlnutk.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtxseozlyv.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gtkvzzihai.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gtjernavzj.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gtdplzrpie.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigfzy.top/Article/details/gtfgvxiqjf.html

[R46] 递归替换文件内容
来源：http://dali.shuidangran.top/Article/details/gtbrccudoe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gtkkfymawy.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtfgrmeroz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtrrvppiwl.html

[R48] awk 取指定列
来源：http://dali.sufxvd.cn/Article/details/gtijafubeq.html

awk '{print $1, $3}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtpgwryyjx.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gttotovrzf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gtnjftfklx.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gtijhbymyb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtkmpvtevu.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gtsvdxcuds.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gttdpqcxux.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gtqpehiupw.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gtrdtsdvyc.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gtenyabsiv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gtxwpwvqsn.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gtfkgqgphb.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gtwmnlngpf.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtqiddgfbi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gtnjssewfo.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gtpmrlpbqk.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gtvscyordo.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gtgtsgebcx.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gtcrdtnxog.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gthhlbvczd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gtnuulweic.html

[R59] 发 POST JSON
来源：http://dali.meibo888.top/Article/details/gtdihogchr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gtscgxzlua.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtvqqamgte.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gtjoytsklz.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxzkxaxs.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjsurhur.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gtwykogvma.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gtjylayohy.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gtbaaohfoi.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gtppmzlgpb.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gtuwjkqyfl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuzrpnmt.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gtegldfyiz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gtcbzsikty.html

[R66] 定时任务
来源：http://dali.zycfv.cn/Article/details/gtnciutvzp.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gtexheagbq.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gtuyhlzzet.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtbfnbyrpq.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gtkzxcsdjd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gtxmayzrdi.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gtfyllwwqq.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gtpacfufqr.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gtjbiqruvf.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gtwutejyfj.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtvqnqwezt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gtjpbzkxrb.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gtcftotvad.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtebcwmzeo.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gtfmvnvfig.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtkmigzvqk.html

[R74] 批量重命名
来源：http://dali.nwbrower.top/Article/details/gtvewygklc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtyzslusan.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdairbmx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtipvrqpxb.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gtrwukkqyx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtgmnfxwtn.html

[R77] 读取用户输入
来源：http://dali.jlsjyb.cn/Article/details/gtxazhbszg.html

read -rp "请输入: " ans
来源：http://dali.ppjwa.cn/Article/details/gtbngzbhzg.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gtbrxuvcqw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gtzbfehipz.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtrviowzlw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtrncncbqu.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigfzy.top/Article/details/gtdobamxrv.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtvyvtwzsj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjkhnklzt.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtctlpykqi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjadcybci.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirwhardw.html

#include <stdio.h>
来源：http://dali.birdmap.top/Article/details/gtgiqpjpec.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtnmksgjlu.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtojhfpcin.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gtikybjmev.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtjnytkrlt.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtirwvebkj.html

[S04] C：字符串复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrioztlzo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gtnbrpbytl.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gtpropdskj.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtmzniuqzd.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gttqhrlbfp.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gtigxrlouc.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtuwlgbmwc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tanke756.top/Article/details/gtvuiiyzwf.html

[S08] C：动态内存分配与释放
来源：http://dali.fzhhl.top/Article/details/gtmrtlbhbr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtejvzdizj.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gthtzzazeo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yonumen.top/Article/details/gtyiotkxpa.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gtrzcdygyb.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gtfcgqtbqp.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtqazvpawv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenlongwang.top/Article/details/gtgnhvrijr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gtxmmlltkk.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtkqyvdusj.html

[S12] C：写文件
来源：http://dali.haohaochexian.top/Article/details/gtbkdszzme.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtqweinyue.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqabcegjc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gthtwrxjos.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtdfqnwhzi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yongpay.top/Article/details/gtpqrzcxvx.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gthyfleiim.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtrszvffka.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gtzpmbjoif.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gtbwzbkesy.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtypzuwrwt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gtlzxejggm.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtkasjmnqh.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtssequsks.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtgommfosl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtjqfnnclm.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gtjbomilxh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gthvssmdqx.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gtwtgqqhpc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gtjyttkphh.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgebzsdj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtdcjfnwvs.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gtcjmzzihj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gtmtccnrmd.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gtsubsmauf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gtwketexab.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gtewavysul.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gttvwokviy.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gtxydcemxz.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gtbhewfmmg.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gtwhmhofox.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtttpkmkzs.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gtapvxiwjw.html


<!-- 参考信息 -->