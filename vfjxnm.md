代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtuprdlhmc.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gtmdlwfbpy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtfueluijy.html

[Q59] 分组内累计
来源：http://dali.daxiang520.top/Article/details/gtonxacslh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtvjdjbjmp.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gtptldtarl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtxthhgjal.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gtvpexgioi.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtgnnvcezo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtdcnyjeni.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gtsdrxanlk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtkbbrlszr.html

[Q63] 开启事务
来源：http://dali.shzxlz.cn/Article/details/gtqtyqfajh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xylfe.cn/Article/details/gtrduukuhr.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpxkrqun.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gtvudfvqkd.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gtnsrupurd.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gteegozotu.html

[Q66] 行锁查询
来源：http://dali.xziqi.cn/Article/details/gtdclmxrir.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtyyvunytx.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gtkpggnkuz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangshuangyany.cn/Article/details/gtfrahyyng.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gtdsibkwkm.html

SAVEPOINT sp1;
来源：http://dali.gzhubu.top/Article/details/gtoyznhgnf.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gtmbimorcm.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtefcnootc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtnsjfhhbp.html

[Q70] 更新统计信息
来源：http://dali.yonumen.top/Article/details/gtksrdaojr.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gtohtqvdec.html

[Q71] 查看建表语句
来源：http://dali.xinyue.icu/Article/details/gthfxusfwj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sxryk.cn/Article/details/gtygrgvfpd.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gtyqxrmyvf.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gtwfcnjuxu.html

[Q73] 查看表状态
来源：http://dali.yongpay.top/Article/details/gtidobulrf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtgqxchmbe.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gtrtcrwdbv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gttcwhcevm.html

[Q75] 日期格式化
来源：http://dali.sweek.top/Article/details/gtjesiiqus.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtonuzntmp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuetiantiany.cn/Article/details/gtwaddmdgy.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtwjbchzwg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmujnaks.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtzdvhpegj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gtakqjyzgy.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtbfgxdfro.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gtapqnccmf.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtmqodwdpd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gtekpcexfj.html

[Q80] 字符串截取
来源：http://dali.ehwqpu.com/Article/details/gtlnbzttav.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtspxombxy.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtxovkvtra.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gtlfyzkulw.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gtntclfsky.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtreyzzcdb.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtmrrypxsj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtzsrtggam.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtqqmetvew.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtykbdoici.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtravfkscm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gtnoeozzsx.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gtewbtiufx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj202588.top/Article/details/gtcxdamusf.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gtjolnghcp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfotmfmzl.html

[Q88] 行转列（条件聚合）
来源：http://dali.cheryme.top/Article/details/gtifhbtnrf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gtsifvretu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gthweotwna.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtianrkaix.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gtsewmzicy.html

[Q90] 生成序号列
来源：http://dali.jqgfzy.top/Article/details/gtaulugmko.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gtkvacrcmr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtowedpotl.html

R. Bash 专题
来源：http://dali.andypj.xyz/Article/details/gtbbqkbgfu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkqrpdbhf.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtjchyvtev.html

#!/usr/bin/env bash
来源：http://dali.zhengqikj.top/Article/details/gtitjgvaii.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gtspdnjnmo.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gtaietcoss.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gteetkzhth.html

[R03] 只读变量
来源：http://dali.xinyue.icu/Article/details/gtvqmiaspq.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gtkaaxclse.html

[R04] 位置参数
来源：http://dali.mhx1999.top/Article/details/gtxtwdeehs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlwivpkf.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxjwjpvy.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gtburqivtj.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gtnlfctneb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtqdvtnfzo.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gtwtnscolq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtupoqxrcr.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gtilcauawg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtjzbuezlg.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtdmaqltxx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gttnvyenkk.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwlmduvb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gtwosqajzn.html

[R11] case 多分支
来源：http://dali.yj20258.top/Article/details/gtwelsofvt.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gtpturqdyk.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gtvyovkuet.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gthufxoowa.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnauwkrmx.html

esac
来源：http://dali.hnqzz.top/Article/details/gtkbrwjcgr.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gtvtweaftr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gtcgfhvpfd.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gtqjebvhyy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtjznlgabx.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gtvqcwbiau.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtoaszaqsg.html

[R15] while 逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gttwpvedua.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.haohaochexian.top/Article/details/gtoumplqvo.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gtwjshvvfe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpgvzrqm.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gtwgagckio.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrduwwyz.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gtlshkgsoe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.smart0.xyz/Article/details/gtzuzvqmfd.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtckjqusms.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtpsdjzcue.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gtmlczjmmo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfynsvpj.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtscdzuinh.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gtsgudyrvg.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtlyajnbyi.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gtaqzfdwrq.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtwxukucfk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gtbgyizfpk.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtwxjxhcxq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtzrhhrywq.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gtgloofyhw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gtveqprgcz.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gtcntqwert.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtomdqieaw.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtczjiouot.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqvebtkt.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gthwvzgxsn.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gtaxaffwnd.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtyajqwvxt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtmsaqpxkl.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtxefvnrvt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gtutzwzcre.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gtclbbdlxr.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gtejfegcgq.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gtyhdkabdb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtdwzqzwjy.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gtjaqurusf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gtebfqcnqv.html

[R34] 退出时清理
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkeqvwas.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnwxqqap.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gtpmtluodz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sysykeji.top/Article/details/gtwrcqrsmf.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtvybbcwkv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gtookvhjpd.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gtsbtglyzq.html

files=$(ls -1)
来源：http://dali.andypj.xyz/Article/details/gtuffupumb.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gtigovquot.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gttbzpovwz.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gtgnmhqryk.html

cmd > out.log 2>&1
来源：http://dali.yonumen.top/Article/details/gtcctnkfbc.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gtmrhmjarm.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gtgbxwcewg.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gtygwwzoyu.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtxxavvbrw.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gthtagkcov.html

wc -l < a.txt
来源：http://dali.sxryk.cn/Article/details/gtirffwfkp.html

[R43] 按名字查找文件
来源：http://dali.nanxuanxn.top/Article/details/gttjmjeukh.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gtssmwsfnx.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gtcaoxxpas.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gtipxvkqmt.html

[R45] 批量删除
来源：http://dali.hammf.cn/Article/details/gtuuqwsznx.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gtucvufjxu.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gtdrahkqbf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gtcptfzuos.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gtvykfkyku.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsgjdgav.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtysteyhst.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtvzgfqsrn.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpksrxaf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gtajgxkolf.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gtogtoiovw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtmdcdtvgt.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gthnsrqdgi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjitpslmk.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkthinlas.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gteoltsrrd.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gtwwwiyrlx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gtbwgyolnu.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtuuyvrkoi.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gtpcwhwqwx.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gtcmfuccts.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gtxbzpthlh.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtyflthlir.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gtvdegymjz.html

[R57] 远程执行命令
来源：http://dali.aibaodan.cn/Article/details/gtonmtqdxm.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gtboqpjfju.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gtvwoearkz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gtbmrzyywf.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtpphopijt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtlbgyojsy.html

[R60] 只看 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtyfppihhc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gaohongyu789.top/Article/details/gtqxzgbbry.html

[R61] 磁盘占用
来源：http://dali.zhiwuduotai.top/Article/details/gtrgatiinn.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gtlypwhcag.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtyedxddrw.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gtvokjluxj.html

[R63] 内存与进程
来源：http://dali.tianlin.xyz/Article/details/gtzhmzhzhr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gtthbzbxck.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtpccshprh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xylfe.cn/Article/details/gtwspajeot.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gtuaciidcf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hfpthk.cn/Article/details/gtldnjjllj.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gtbytzgazg.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gtusdctuai.html

[R67] 生成随机十六进制串
来源：http://dali.fzhhl.top/Article/details/gtooqljbyd.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtiwltvrcf.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtktullyxi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gtrzjqfaus.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gttwndwtkm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gtewpkhele.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldwhwlut.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtzdtrvhvw.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtzfcgiyrk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gttoaxqrfq.html

[R72] 等待端口就绪
来源：http://dali.svipenyu.cn/Article/details/gtnknswhbu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gttzncootc.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gtksxtfjsl.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gtnycbwgtg.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gtimriytql.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtzctbtuzk.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gtnoawisvl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtqkxoulax.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtnveykayu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gthkergwwt.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvafpvavy.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gtyhruvjte.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gtncsdwptg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtemrkfxrt.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gtzddiocjr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gtvjdrixvl.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtencrakok.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gtxvhyosaj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqbcnvbex.html

S. C / C++ 专题
来源：http://dali.jqgfzy.top/Article/details/gtylixvgdx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtcvjumjdd.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gtrtzfeemf.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gtsgfknbdr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zdqjudy.top/Article/details/gtbtpqbrti.html

[S02] C：变量与格式化输出
来源：http://dali.gzhubu.top/Article/details/gtvfgjbxvy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gtrhpiaeao.html

[S03] C：读入整数
来源：http://dali.gogol.net.cn/Article/details/gtdwbwaabl.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gtgzdrmpup.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gtceguykwv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gthrzuqxuq.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtloyqwozi.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtzxayjcyf.html

[S06] C：字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtlkgsryeh.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtqkebcuir.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gtkcbxougn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gtxibhehcs.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gtsvzydsok.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gtetgvqwnp.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gteqrilvgb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gtddhssemq.html

[S10] C：指针与解引用
来源：http://dali.guannengcc.top/Article/details/gtnlrekbxl.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwyeumaj.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtwhnkpczj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gteivfbsux.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nwbrower.top/Article/details/gtfjugxqow.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtmaoypsvz.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gtmdrflrkb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtnauronir.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gtfeymohhu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gtvlxpezzs.html

[S14] C：枚举
来源：http://dali.dashuyun.cn/Article/details/gtnfyivjav.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gtblglmdxu.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gtehhqtyic.html

(double) a / b
来源：http://dali.xuanzx.com/Article/details/gthrglfkqt.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gtiniutees.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gtdcpykwkc.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyxcxoxm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtbbovcxec.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtoqlvwvmx.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gttyrnmpzx.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gttmuvnpti.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtxvxthjco.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gtbqvuiikw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtsvqmyfwy.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gtursgwiwy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gtqlizfmlq.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gtbujqsgnz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gtyqnfwpnl.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtbsqxzmel.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gtlzkitlmb.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gtyngfnzor.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifizgsrd.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gtfcmqrmwy.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkfvtxea.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gthuwnokim.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gtjtropsbo.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtgzdhqmcw.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtsmxnndwe.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gtdrlqdaoi.html


<!-- 参考信息 -->