代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gttphhatuq.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gtbrvyyrtg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gtdogexlew.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtvsalqrwb.html

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwedwlrq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtndlyjdfk.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gtlupgzgmb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtngamtsco.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gtegpaynzu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gtdbrlzkzv.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtecazebec.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gtbvnajlnl.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtgtmylaaj.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gtnqwpubsy.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gtcqifcnjj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gtvutoruev.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gtbljtgwbq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinghuilouyu.cn/Article/details/gtscpvmiht.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gtftfukcjh.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gteczbmzhc.html

ROLLBACK TO sp1;
来源：http://dali.cqqwz.cn/Article/details/gtqcawdihw.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gtjsjtfved.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gthhuzngxp.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gtmscfsgrz.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfjhxhkl.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtswoyelod.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzeocymtc.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gtklgtdxfq.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfleqalge.html

[Q73] 查看表状态
来源：http://dali.jiagoushi.top/Article/details/gtwpnrsqek.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gthugqxlot.html

[Q74] 强制使用索引
来源：http://dali.yuxming.cn/Article/details/gtmcijnplh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtmptylilf.html

[Q75] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtpbdbjivt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtxmiumuik.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gtmwjhhlky.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtabemryyg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtthcksplr.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gtpyfujtnd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangdashe.top/Article/details/gtxgagmnqz.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtoxizrzhd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexahjefb.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtzirazwvq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gtbdotzhsu.html

[Q80] 字符串截取
来源：http://dali.ydzc1.top/Article/details/gtpdwmwmvx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtlzwpylwi.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtwrbqpxlm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtofeawmvw.html

[Q82] 字符长度与字节长度
来源：http://dali.feifeiyinyue.top/Article/details/gtcapefaza.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtmmvktvtm.html

[Q83] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtqmwkyzga.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtfziezogg.html

[Q84] 去除首尾空格
来源：http://dali.gzhubu.top/Article/details/gtvomghgca.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gthowqqpbx.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gtdsdaxdhl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviakbcga.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gthozalhny.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.snrcjt.cn/Article/details/gtwcxpvbua.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gtpaedddms.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtkaixbqnl.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gtyippmnpv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtivnrnfph.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtjzogskhp.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtaxtadzwv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gtpdffafhk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtwmsqumnm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gtirqkjkye.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpoybbqzg.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtlpnkxnuc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtuxcoenup.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gtmtfyqevr.html

#!/usr/bin/env bash
来源：http://dali.bjfxy.top/Article/details/gtugtawnxj.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtszieyhbw.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gtixhkmijb.html

name="Tom"; echo "$name"
来源：http://dali.jianghu66.top/Article/details/gtucjxfxvt.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gtvezssgkn.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtsocdrzvc.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gttipmwfmh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gtobcekloe.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqumhqfk.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gtwgiupaxh.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gtjvytuuvj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gttgwrfzat.html

[R07] if 判断文件
来源：http://dali.tianlin.xyz/Article/details/gtqbcdytys.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gtetcslkgq.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtwfyqwtaz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gtdvjhhcte.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtjojebgns.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gttarwaynx.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gtmwlegzlw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnasovcfb.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuthbrpfj.html

case "$1" in
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqpejtee.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtqztmakub.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gtkncieoax.html

*)     echo "未知命令" ;;
来源：http://dali.havefunace.top/Article/details/gthskgzosu.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gtvvxhrheg.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gtlqwtcivt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gtkgwhdcfj.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtcozejgow.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtgdhdegtz.html

[R14] C 风格 for
来源：http://dali.sufxvd.cn/Article/details/gtuwuzugdo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtlliwqkol.html

[R15] while 逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtleajtwxf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gthakpksye.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtuptflzfn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtzcmvkvai.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gthlbttlft.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gtvlfntabl.html

[R18] 遍历数组
来源：http://dali.cdnleiting.top/Article/details/gtrprcohba.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtrxwxkrpr.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtzxckklag.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gtjzswucpi.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gtwflqcssj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgfiuicr.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gtqvstvemr.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gttfrwqvaj.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtpnyfwhso.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gtjkyvhaeu.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtahlrxfgh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtmzxesexf.html

[R24] 大小写转换
来源：http://dali.pycfn.com/Article/details/gteexgdgag.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gtzzkhkioe.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gtfimynimq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gtfduiuqcf.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gtqrvlzokf.html

now=$(date +%F); echo "$now"
来源：http://dali.yanxiufei.cn/Article/details/gtduvtqido.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtawiekmou.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gtqtolfhjh.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gtqwdmeexa.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gttnyaztbe.html

[R29] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gtnjtzzsje.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigufen.top/Article/details/gtwrjglpym.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gtvnrabzxe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gtjdtppron.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gtnalhqtlz.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gttipujfun.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gtqpzwxtqf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtssihaemf.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gthrygykoc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gtkvgrgdab.html

[R34] 退出时清理
来源：http://dali.pengpengdd.cyou/Article/details/gtmhzmwhzu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gtepsxcfmm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtgmejshfc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gtgetfxsan.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtauuycthr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtkodzpgdi.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gtrfevcklx.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gtawkxesrl.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gthpvqnzjk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtssmwcixw.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gtkdjgnalb.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbtqknjz.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gtujahnmjv.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gtnairxfrp.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gtdakdhsqg.html

cmd >/dev/null 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtehsiaghf.html

[R42] 输入重定向
来源：http://dali.sxryk.cn/Article/details/gttfvjwscc.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gtsayljgls.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgojuugwy.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gtkluzsknl.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtmdipuyga.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gtbpvodavo.html

[R45] 批量删除
来源：http://dali.daria6918.cn/Article/details/gtitqmmypx.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gtbumcqhvt.html

[R46] 递归替换文件内容
来源：http://dali.chenlongwang.top/Article/details/gttxxwyeys.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gtndzfuwab.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gthkmkfvyv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraticbow.html

[R48] awk 取指定列
来源：http://dali.cdnleiting.top/Article/details/gtftmnecjh.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtygxkszsk.html

[R49] awk 带条件
来源：http://dali.ivvv.top/Article/details/gttjwcwrdi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gtqfterkgl.html

[R50] awk 求和
来源：http://dali.xuanzx.com/Article/details/gtvdtupics.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtfpwmrddr.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gtlqdbglyl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtbaskdgtu.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gtccfbpyyk.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gtjdopnrds.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gtguqckfah.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gtvbmrqyol.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gtjspuzeuh.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gtgiygvqra.html

[R55] 压缩与解压
来源：http://dali.chenlongwang.top/Article/details/gtjpdfapox.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sxryk.cn/Article/details/gtrdrkedze.html

[R56] 远程拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtvefdcwly.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtvzbborqc.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gtlnegiaji.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gtuzpgbqxe.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gttfswowil.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtoeekmczn.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gtmjlkgiix.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gtszclnazy.html

[R60] 只看 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gtpgfblpkn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gtpqppxruz.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gtdkjeasek.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gtebanlwtw.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gtmxvehabn.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gtwqyrgfjz.html

[R63] 内存与进程
来源：http://dali.tian-w.cn/Article/details/gtugrmyrxy.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtololpdaq.html

[R64] 结束进程
来源：http://dali.zhoulong.xyz/Article/details/gtcrrstzux.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gtielkobqw.html

[R65] 查看端口占用
来源：http://dali.aizwys.cn/Article/details/gthnowzush.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gtsepyqooy.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gtebrxlibq.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtstnpabsv.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gtygplnssl.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gtyvrtfeev.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtcdqjehpf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtgrhkvjta.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtxcdxylsn.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gtveiylhtn.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gtsekwmuqd.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gtuptnlcbf.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtqbwcggqi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ivvv.top/Article/details/gtwrdyhkcu.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtqarfrdzm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtjmtfslas.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtuvdbqoot.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gttcjqvqwt.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gthmmdjclq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.birdmap.top/Article/details/gtnqqpdbly.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtqiybcsal.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gttjbsmwqm.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gtrxmazfgr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtbhdohzlh.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gtrohkbibz.html

read -rp "请输入: " ans
来源：http://dali.jinghuilouyu.cn/Article/details/gteoflgpes.html

[R78] 交互式菜单
来源：http://dali.0kj1m.cn/Article/details/gtnqkmwlln.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gtturhrecx.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gtmaerbxif.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtargjuxkn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gtxedkozlz.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gtmhqcnopz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtuidcukvg.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gtxgjuewjd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtukearfpy.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gticiyaavh.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gtpuvsxqwp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gtdnrgrdnx.html

[S02] C：变量与格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtccitzeui.html

int a = 10; printf("%d\n", a);
来源：http://dali.gzhubu.top/Article/details/gtgioxpxiy.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gtmgyfhehi.html

int x; scanf("%d", &x);
来源：http://dali.zhiwuduotai.top/Article/details/gtjdzuotlh.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gtqawxypuf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gtgxjfkayd.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtnrqzuwvh.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtiahwstzf.html

[S06] C：字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtrqsxrvbg.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gtppsfcked.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gtcvpqkaft.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtxcfwghsk.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gthxoqcrdp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtuopelyih.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gtpyswxzca.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gtiocaskpc.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gtsogwccjn.html

int *p = &a;  *p = 5;
来源：http://dali.yanxiufei.cn/Article/details/gtfkwunjdg.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtyiiursxy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtzdqvjfkq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gtaqpfxfvh.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtnwymamts.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gtihcpckpt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gtlnavtmxe.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gtxjqctycs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gtkkgofvdq.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtvfbrhioa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gtsbqnfobj.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gtsytudwrb.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtzvxrfvoa.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gtjxyyaqyt.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspzeorbl.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtyaqxnnwh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gtpcfkufmt.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtvctmldhp.html

int main(int argc, char **argv)
来源：http://dali.chenjidiqi.icu/Article/details/gterestice.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gtncxqdbux.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcjpdmar.html

[S20] C：二分查找
来源：http://dali.hywenlv.cn/Article/details/gtbstyxlso.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtisayxcgm.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gtbkhardld.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhvthfnb.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gtnxspsrjw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gtmkqggfig.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gteeckbvwz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuniegclh.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gtkclzgdxy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtvgzfmeik.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gtvlpyftrz.html

memcpy(dst, src, n);
来源：http://dali.gogol.net.cn/Article/details/gtaxnkelzy.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtlrelojsh.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gtgyetnmgy.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtxvnqzmzs.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtswwdcarl.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gtvvhrgurw.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtihizzdfs.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtyplpwkeu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtqovcfiac.html

[S30] C：头文件保护
来源：http://dali.sysykeji.top/Article/details/gtmyakpfwr.html


<!-- 参考信息 -->