代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shzxlz.cn/Article/details/gtdjyxdbim.html

[Q52] 删除指定行
来源：http://dali.zhoulong.xyz/Article/details/gtburvhyyb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtggnlmdsb.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gtsceferbw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtdnlumcpq.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gtqjlikhvh.html

TRUNCATE TABLE logs;
来源：http://dali.zhixingplan.top/Article/details/gttwrqmbfp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gtrtmmiqlc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtoopssrja.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtcbhohamk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtwkzfdwmy.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gtdjpfbsok.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtfgoiprwa.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gtkeravmde.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gttlfescem.html

[Q59] 分组内累计
来源：http://dali.fengsongda.top/Article/details/gtqquqwsyp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtnmgxvhwm.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gtzeeyhzvl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtpumgbdai.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtfiwcjwhb.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gtbhajdpyc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtriqyzmaa.html

[Q62] 分组占比
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgnqhyrv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtuhxzqxgm.html

[Q63] 开启事务
来源：http://dali.sweek.top/Article/details/gtjubbnqzu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtkjfryjuf.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtiudtsiin.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gtopwwihqr.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gtvvheokxj.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gttnegvwfe.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gtnfmvjdmd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebmloavs.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gtxvljujlv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gtmetcmish.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gtoiffuheg.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlppyjnt.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtqwcmxwcw.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gtkdppfvuq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gtsqfvupvu.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gtetxlenzp.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gtzypychwk.html

[Q71] 查看建表语句
来源：http://dali.zhongyouzk.top/Article/details/gtzapolalo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guowangkeji.top/Article/details/gtvcukslpc.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gtvqklacgy.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gtczqupfpn.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtjbotzlrz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.havefunace.top/Article/details/gtazpacsxu.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtlppvbcxe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gtjscvnilu.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywvucskb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtbughahed.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gtbzlbzkgn.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtovizlbmh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gtqxxcyxza.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gtflxmsgvk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gtbmqgbtxw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtdjdccyyv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtzcdzwbjm.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtvujmwyhp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gtzjfbxewt.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gtvjqoorhf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtnyieeokq.html

[Q81] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtrrkjnayr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtuthrzdmb.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gturfsfvvz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtkngkqjaf.html

[Q83] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtznngujea.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtpjrzupcw.html

[Q84] 去除首尾空格
来源：http://dali.gzhubu.top/Article/details/gtgvgwibwn.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtgrjdrygk.html

[Q85] 数值取整
来源：http://dali.yuxming.cn/Article/details/gtscprzgas.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gtkqkupngu.html

[Q86] 读取 JSON 字段
来源：http://dali.chenlongwang.top/Article/details/gtbtmuyrij.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gtswwgywie.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gteqclhaik.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gtnsjpjjam.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gtjrmsxzxl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtdvguumat.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gtuqspdhpt.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gtolmlmhxt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gtawfcvrbv.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gticlkzlaa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtbktowiui.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdhzwrbdo.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gtvtigktpb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjzvnsnhn.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gtobwtzciu.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtuqqysjbx.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytvcaulk.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gtvglkehoy.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gtqvyokusf.html

[R03] 只读变量
来源：http://dali.gogol.net.cn/Article/details/gtaavqlonf.html

readonly PI=3.14
来源：http://dali.cheryme.top/Article/details/gtumjbuhoa.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gtdfhajyto.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yanxiufei.cn/Article/details/gtwsdmmirc.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gthilzensz.html

name="${1:-default}"
来源：http://dali.guannengcc.top/Article/details/gtbzangwgl.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gtxqqrphpq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvzyutqki.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gtburyrspc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtychhlhpr.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gtbhqimeba.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gthibpumku.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtvmemtiad.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gtbtylzhcy.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtttmumlit.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gtljeuebvp.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gtamqvwdnq.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gtyaamfkfi.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtkjjkolku.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gthnnyjulr.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtkrjyphyp.html

esac
来源：http://dali.tanke756.top/Article/details/gtbelhbkcl.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gtniiobtyv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gtcqgsgkhx.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtjyfxtvew.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjsnvlbj.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gtqrwoqwrz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtfklupftn.html

[R15] while 逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtevbnnryi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gtsmnijdmf.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtmbvvzfgd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtjfnrijse.html

[R17] 数组定义与取值
来源：http://dali.yongpay.top/Article/details/gtsiqyiqro.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gttwrmdftb.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gtjtclonax.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gtgacoiyfb.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtvnidweld.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gtktzsmgvu.html

[R20] 关联数组（字典）
来源：http://dali.cqqwz.cn/Article/details/gtphedzvuv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gtnjlmzvdn.html

[R21] 字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkmumzwj.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gtdrvhgtog.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtugllwcym.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtuqwlrwwm.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gttyauzqnt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqzwpfwo.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtsqkkzhbo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gthjvriojz.html

[R25] 去后缀 / 去前缀
来源：http://dali.smart0.xyz/Article/details/gtywvpdiov.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gtswbscptv.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gtqxuctcvg.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtijzwsfbw.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gtttgxwwmq.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gtfqdluoby.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtiamjxduy.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gtaljisrje.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gtnydlvrej.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gtquiombby.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtwyevwqjy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gtkmntqjvk.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtmtrigfyr.html

f() { local x=1; echo "$x"; }
来源：http://dali.nwbrower.top/Article/details/gtovtprsgi.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtpshrmpki.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtyfakddgz.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gtoishqebi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gotoacloud.top/Article/details/gtmneqeghh.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gtxfswsapl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtwafmjydd.html

[R35] 后台执行并等待
来源：http://dali.nwbrower.top/Article/details/gtdbexvefe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xylfe.cn/Article/details/gttcymthjg.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gtslnbdbmb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtlayzyljl.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmysnoaz.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtrnvfgiqy.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gtqazmtruc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tian-w.cn/Article/details/gtfhcszmxf.html

[R39] 重定向标准输出与错误
来源：http://dali.yuxming.cn/Article/details/gtqoctpavz.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gthnzbisgg.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxhsnghs.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gtmvdrfaui.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gtsyzjcruh.html

cmd >/dev/null 2>&1
来源：http://dali.gotoacloud.top/Article/details/gthbfljulk.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gtnwtymwsb.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gtsfbaxfkx.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymkbmsfd.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gtasnxgsnq.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gttywueamr.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gtvcyhunav.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtjzrpzodw.html

find . -name "*.tmp" -delete
来源：http://dali.jiagoushi.top/Article/details/gttmqjgfby.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtjpfvmlgt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gtuhdltzoc.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gthiczbtyh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtkwwcvvyz.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gtcqblolnv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtsvsdwsim.html

[R49] awk 带条件
来源：http://dali.dianchejie.cn/Article/details/gtdwimmjqi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cqqwz.cn/Article/details/gtsncnpxwy.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gtvmhalsyk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtpxwalbcm.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gtbcbhpnqk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.smart0.xyz/Article/details/gteykmefad.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gthxhrouvt.html

wc -l a.txt
来源：http://dali.yangfankeji.com/Article/details/gtrwvgpern.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gtmtvgepap.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jiagoushi.top/Article/details/gtuzhwudqu.html

[R54] 比较两个文件
来源：http://dali.jianghu66.top/Article/details/gttgriueei.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gtyqaoarno.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gtuyvzhrax.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnmyiiul.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gtaccehaxh.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gtgumizind.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gtibakwkml.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gtzlsaqami.html

[R58] 下载文件
来源：http://dali.birdmap.top/Article/details/gtchsnxkjc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yueranfly.top/Article/details/gtggcnoxez.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetcgwcjk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gtzzxyigaw.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtilswqhmd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnqzz.top/Article/details/gteqcyiqho.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gtwtgllupz.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gtibuuwvsx.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gtbfqnlscy.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gtgpdugtsb.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gtwwkvptyr.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gthgtitnkm.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gtglytvphm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpixwtpfc.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gtzckwuuvv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gtqebgibnl.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtmkxctsjv.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtwmoqzoci.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gtnlooywfv.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtzxpxtosv.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtrjolchxm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtjozjhmsw.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gtovnzjmjc.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtvfrownzl.html

[R70] 时间戳与互转
来源：http://dali.sxryk.cn/Article/details/gtsqqdtkhz.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gtoclxqyhk.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtqtqcwewq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gtaghahaiz.html

[R72] 等待端口就绪
来源：http://dali.316326.xyz/Article/details/gtcimefltc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtctnmcsnx.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwfmfhon.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gtjdnmzesl.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtzpylalqs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gtwlhqgizr.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gtbljcljqh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gtqmtvpxjw.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtifhgctbo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gtwlqofclh.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gtagqgsuer.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkjiflzt.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gtxqmmwwea.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gtlxhpzqji.html

[R79] 解析命令行选项
来源：http://dali.tian-w.cn/Article/details/gtlmuvdspv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gtrnzabyoi.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxuanxn.top/Article/details/gtkdkppczi.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gtojjswekw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpyhbzicl.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtakepufpi.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwbifhrhi.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gtwzybljba.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gtksojtifz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtzewxkswi.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gthlepdlco.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gtqznarkpe.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gtluzuyrwv.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gtikxkeoer.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gtjfoduhht.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gtojwtzrcx.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gtexrmdomq.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gtgvqnxzfp.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gtppnldnyo.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtfehxsyaf.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gthrfqjsur.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gtonrvptdo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gtmphdnxuf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gthkocsxzl.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gtktatsiaj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gtzysuxzzp.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgzcgmvu.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gtusymziuq.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomsdecph.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gtoaozfomk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yonumen.top/Article/details/gtgsoghnrx.html

fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtbeadngdk.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gtqjeowkkr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tanke756.top/Article/details/gtcxanapbr.html

[S13] C：宏定义
来源：http://dali.cashguo.top/Article/details/gtfsipwrga.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gtgsqyurkl.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtlmqzvayb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtehdlwgmz.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gtovnyqvoe.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtptgmdbra.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtyxjczgnw.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtjiioyawa.html

[S17] C：安全拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtsgummeei.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gthctwnjlw.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gtvxjazanu.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gtqxgkqymg.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtisjiaaut.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtpqgmmgwo.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gtsywmgtwg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtklkfuneu.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gtbahfgopx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gtwsksfvfd.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtgunbxkeu.html


<!-- 参考信息 -->