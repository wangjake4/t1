代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jiagoushi.top/Article/details/gtkmzunjea.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gtfhbkggap.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtzkzovlds.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gtprjvfuku.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtyxqlzmup.html

[Q54] 清空表
来源：http://dali.zhongyouzk.top/Article/details/gttgxmkgbe.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gtyfgrxeva.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gtxqtrcbkl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtizgfbpvk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hywenlv.cn/Article/details/gtuqdsyxzh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtlpupafdq.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gtgmeloysk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtjmztsmyr.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gtfvngramm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pycfn.com/Article/details/gtbwfmlnpr.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gtvecqthxq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtdvrugzlm.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gtproozoiw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gtbflcexrk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gteyqlctns.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gtwlkqgovi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtlrpaopia.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpcerrpw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtopigqzat.html

[Q63] 开启事务
来源：http://dali.ehwqpu.com/Article/details/gtakrqxakx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gtvfafxeel.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gtlxcubumw.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtphjlfzlt.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gtpjdumxsx.html

ROLLBACK;
来源：http://dali.ydzc1.top/Article/details/gtfdjxgydl.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gtftkpuluo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ehwqpu.com/Article/details/gtxrneizui.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gtohpbbonq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gtwohlnvjg.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtxqcrfwrv.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gtaxcqehps.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gtmgdtzxwd.html

[Q69] 查看执行计划
来源：http://dali.dianchejie.cn/Article/details/gteofpfquf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gtsdgxffmy.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gtkbtmerkr.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gtqseixwrr.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtgqvzczlu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gtidkdqnim.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gtwwfirlbm.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gtewidevbt.html

[Q73] 查看表状态
来源：http://dali.yuxming.cn/Article/details/gtsbdhzrrt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gtonomxqdv.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gtqwsedzkj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gttpwayiyf.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gtfsrvwljx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtlmckpgcc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gtkwobbbec.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gtnfhvnups.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.quarkkingdee.top/Article/details/gtsiiktbwi.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtwilbpzte.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtktosydgd.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gtswvuykwq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gtfzpowxmi.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gtycethvnp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gtjeiuysah.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtrxjgtxkk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtykrhpzhd.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtrypiowzl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtyskwtrae.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gtnarwctih.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtzcmoyaam.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtfwxoqudm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gteockdeyh.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gthqtcuxkl.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtiffptuwa.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gtfzlefbzs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gtrsvkhmpy.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtpkzohzfu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gtrcejqdgf.html

[Q87] JSON 字段做条件
来源：http://dali.iojbl.cn/Article/details/gtxtbbxqwn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gtnfkzratt.html

[Q88] 行转列（条件聚合）
来源：http://dali.xinyue.icu/Article/details/gtlvpfhnxi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.kuanghao11.cn/Article/details/gtresydbyt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gtqmsdtdtn.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gtjtbcdrmg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gtkazxclnu.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gthmmimjch.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.vqdsnc.cn/Article/details/gttjdszydm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfybbwasy.html

R. Bash 专题
来源：http://dali.iojbl.cn/Article/details/gthkleqwnv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtsbahlfsw.html

[R01] shebang 与严格模式
来源：http://dali.feifeiyinyue.top/Article/details/gtbcbgrsjk.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gtpshvisjb.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gtjilpwkhg.html

[R02] 变量赋值与使用
来源：http://dali.haohaochexian.top/Article/details/gthvrqxnbs.html

name="Tom"; echo "$name"
来源：http://dali.snrcjt.cn/Article/details/gtygnjrlsm.html

[R03] 只读变量
来源：http://dali.wangdashe.top/Article/details/gtllephhnr.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtrwlkamvb.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gtzzobmqjk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtqjuvsevp.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gtsptadlrb.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gtigawinao.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gtsdhfabjv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtkclihtvk.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gtmbtypgvs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gtzjqbrkvu.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gtiomwarqa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtbwwwithe.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gtylijxrjc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gtktznjdgl.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gtoueutiij.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gteuquodve.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gtuirhtxhi.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gteqkuatwt.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtkmichcsl.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gttsnsaliw.html

*)     echo "未知命令" ;;
来源：http://dali.sxryk.cn/Article/details/gtuwqwxtvk.html

esac
来源：http://dali.jianghu66.top/Article/details/gtdmvmlfzv.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtbbxyzqwj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtoldalbuq.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gthgjaryyg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtyiwnxfuy.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtgswsmjht.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtbcgnghwb.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtrtmauaqe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gtzqpcotqk.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gtluzmymil.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtbmzlzabw.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifgxgjog.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gthqmtokyi.html

[R18] 遍历数组
来源：http://dali.gogol.net.cn/Article/details/gtxbtquzpb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gtwtimofrc.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtelewjviy.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gtxrbvutzr.html

[R20] 关联数组（字典）
来源：http://dali.birdmap.top/Article/details/gtibeicmgu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yangfankeji.com/Article/details/gtljhkdjey.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gthgqkuhls.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gtpomgrnxh.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtdvcvqwdc.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gtopvrtilf.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtisvftmvx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtjxhfshhy.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtugjxicsc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtuifvfqdc.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gttszorqkt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gtkyyhzjgg.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtueyzscbc.html

now=$(date +%F); echo "$now"
来源：http://dali.hongshengwenyu.top/Article/details/gtvsqhjqao.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gtzbvpjzxg.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gtptivaohl.html

[R28] 浮点运算
来源：http://dali.hfpthk.cn/Article/details/gttdganijk.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenzaomai.com/Article/details/gtoovyeyzq.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtmkqccplt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gtuziyydrb.html

[R30] 函数返回状态码
来源：http://dali.pycfn.com/Article/details/gtcoggojuk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gtjtnfqohm.html

[R31] 局部变量
来源：http://dali.andypj.xyz/Article/details/gtqbcimcak.html

f() { local x=1; echo "$x"; }
来源：http://dali.redwolf501.top/Article/details/gtmvmzkafc.html

[R32] 参数个数校验
来源：http://dali.dianchejie.cn/Article/details/gtasaxkjyk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtrmlqlufu.html

[R33] 捕获错误并提示行号
来源：http://dali.cucudq.cn/Article/details/gtjxzefipb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtadjovsjq.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gtzaiawfgz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtjyildqlt.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtdlyscmkz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gtzvzziksf.html

[R36] 并发执行多个任务
来源：http://dali.yongpay.top/Article/details/gtdefovhbu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yongpay.top/Article/details/gtwcdrevhb.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtoiflskjw.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gteiulouto.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gtlqzmeels.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gtogmfwpfi.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gtarejqwqg.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtfugcnozp.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gtpmqzxchr.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gtdllasklj.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gtappeexpb.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtouemarck.html

[R42] 输入重定向
来源：http://dali.xuanzx.com/Article/details/gtwfnpdjbq.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtepfkfzmm.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtfuhhdhkc.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gttjztysih.html

[R44] 按修改时间查找
来源：http://dali.gotoacloud.top/Article/details/gtwshdflqi.html

find . -mtime -7 -type f
来源：http://dali.yj20258.top/Article/details/gtnlovtpop.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gtozcijqur.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtqtwanwuk.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gtsyjyrvwn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gtpgsocide.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gtxnfkchrn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gtgnxxkzeq.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gtfznsnaot.html

awk '{print $1, $3}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtrrokhzty.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtmhrpbsnc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sweek.top/Article/details/gtbirohynd.html

[R50] awk 求和
来源：http://dali.chenlongwang.top/Article/details/gtdwztxutp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.birdmap.top/Article/details/gtlqychcuu.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtoobkqskx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gttewpzukn.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gtcwifibme.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gtymjczzxj.html

[R53] 查看文件头与实时尾
来源：http://dali.cucudq.cn/Article/details/gtwazujevd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodovvdew.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gtbbzqbeyb.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtqqpqpxhj.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gtkydmxdoe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gtjnonzhgv.html

[R56] 远程拷贝
来源：http://dali.yangfankeji.com/Article/details/gtklajtixr.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gtajmremoq.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gtacsvtnpd.html

ssh user@host 'uptime'
来源：http://dali.chenjidiqi.icu/Article/details/gtbazjgvpn.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gtfyxfmmlk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtqjegduib.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtsgtrmtzj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gtbqvlzuzm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtjmrdrnco.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuxming.cn/Article/details/gtgwnqrpeo.html

[R61] 磁盘占用
来源：http://dali.chenlongwang.top/Article/details/gtmgpjmskr.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gttfaljqsx.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gttnmsdshf.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gtrkcstebq.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtiwqrdzil.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gthayzajin.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gteexdgbty.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gtbxurpase.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gtwqgammcz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtavlmdjqf.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gtvmhlzcnl.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gtitegasdm.html

[R67] 生成随机十六进制串
来源：http://dali.sxryk.cn/Article/details/gtyddunohl.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gteslvtbyp.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gtzfllnpks.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xziqi.cn/Article/details/gthcpelctf.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gtvvpfjxcy.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtrmtuvybu.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchberuvw.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gtorwurrac.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtdqrgeulr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gtjyouktfr.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gtvhvkyukw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gttbtqumbn.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtabczopzn.html

split -l 1000 big.log part_
来源：http://dali.ivvv.top/Article/details/gtgvqbqgzc.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtrgojnuyl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gtjzcjatgu.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtqgzzrwmt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aibaodan.cn/Article/details/gtowoprtzg.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gtdneewqpu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gthstdbgkj.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtkwumxhfv.html

read -rp "请输入: " ans
来源：http://dali.aizwys.cn/Article/details/gtokbzscqr.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gthbygrzxf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sysykeji.top/Article/details/gtrtqcekke.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gtuvmxzlgh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gtdoadqnxi.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gtnerdtlvi.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtwbkgdvlj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtctuwadns.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gtxxodsvcu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gteftcqxvw.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtmeplwisj.html

#include <stdio.h>
来源：http://dali.tianlin.xyz/Article/details/gtxlawixfr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gtmmfcryug.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gteihfjggj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtrfpkvdjf.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtpfouurba.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gtzdbqmcbo.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gtuewrgkmo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtucbkbpaw.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtndcoceob.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gtscqbxcds.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtsfnkrwjp.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtefsdwbcj.html

[S07] C：数组遍历求和
来源：http://dali.yongpay.top/Article/details/gtvfoenson.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gtyfczumrc.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gtitqoiupx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gtxlqpwcap.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gtqgbjpzln.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nwbrower.top/Article/details/gtgjxaczuz.html

[S10] C：指针与解引用
来源：http://dali.yj20258888.top/Article/details/gtmpivkbga.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gtipbtqzax.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtnwgnmhsa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gtfdpqvftj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gtkgmqorac.html

fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtwosphocw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gthaogizjd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gthpqeegbm.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gtbpzrjbch.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gtpqtdgquu.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gtnvwaxegj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtdewfrcmk.html

[S15] C：类型转换
来源：http://dali.cashguo.top/Article/details/gtwyjvfsxj.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtoongecsn.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gtogymquha.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtqdrfjska.html

[S17] C：安全拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtaxwswxoz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gtbnsapsel.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtsmyxibal.html

int main(int argc, char **argv)
来源：http://dali.nanxinkj.top/Article/details/gtkbcrusro.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gtxrrjrrjz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtocajmflo.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtfxctcswr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtcotuutvo.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtcmbtzrzh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtvcqofcii.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gtykzqntam.html


<!-- 参考信息 -->