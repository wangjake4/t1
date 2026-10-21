代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtbglwuuud.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gtviygzqws.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtsuaamwnw.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gtbughzxvh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gtjsalgmoy.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gtmprenlsi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtiyponxha.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gtpoaxtwqd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zycfv.cn/Article/details/gtnaiommys.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtdqtyqnti.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gthulmjgwt.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gtfscofdej.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtwmgmvzia.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtxvaivkwd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtbnpjkubj.html

[Q57] 行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewpabgra.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gttfxunzce.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gtcdhixnck.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hammf.cn/Article/details/gtgzmehiyl.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtgdrjxxff.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtpktvoliu.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gtpppdrgab.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gtkadyjksu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtdjhbyyqw.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gteuvelazy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtyrcrstjk.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gtqypjkamt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtegzzxxva.html

[Q63] 开启事务
来源：http://dali.fzhhl.top/Article/details/gtlgqjqnig.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gtfkxoyuou.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gtojjswjhm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtglathjok.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gtpibbsuka.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtttigivck.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gttdmyeuei.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangdashe.top/Article/details/gtzauymdif.html

[Q67] 设置隔离级别
来源：http://dali.xziqi.cn/Article/details/gtmrlkdaes.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gthesgrduh.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gtnheqouyl.html

SAVEPOINT sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtovgmtthe.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gtofglgqzh.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gtacdwmvdv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsoagexo.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gtduzmjzqk.html

ANALYZE TABLE users;
来源：http://dali.xziqi.cn/Article/details/gtcrdnactf.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gttrmaasfo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtfmmecldz.html

[Q72] 查看索引
来源：http://dali.redwolf501.top/Article/details/gtdhszptoa.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gtdrimafux.html

[Q73] 查看表状态
来源：http://dali.xuetiantiany.cn/Article/details/gtynmwnpte.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gtmxcxraxq.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gtosjyyyvh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gttkmzhgwh.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtbxbqglua.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gtejnqwqfu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gtgfvpiebt.html

[Q76] 按天统计
来源：http://dali.bjfxy.top/Article/details/gtbzvazhfi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gtccxshazi.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtnpszvcky.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gtdvemfzxc.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtduhtolwz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gtdqsokded.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gteqakuowt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yonumen.top/Article/details/gtkibhswzm.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gthkyzvzil.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtchrmnnls.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtfntfmrye.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gtqylspxix.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gtbbsxoenb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyuzgcfo.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvfasbey.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gticwxoeca.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gtdclnkhnr.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtfttjlcum.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtmcikjpec.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gttqrqacdq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfkelwhq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtmftrecip.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gtylhopjfe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtcyjjhtkw.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtywhzcgra.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gtutkzuuil.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtqypzugtw.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtkbomzkok.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dashuyun.cn/Article/details/gtsnewzxus.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gthjchmnnj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtczlwlygc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtiprozrvx.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtjcymyxym.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxaqvvod.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gthqlsppta.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gtlvhicxrj.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gthocqikri.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gtkjtwvors.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gtkdislrzc.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gteumgcmut.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtjrrcnfuk.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtyadadpjs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gtldzdqrjn.html

[R05] 参数默认值
来源：http://dali.xuanzx.com/Article/details/gtnixrqrla.html

name="${1:-default}"
来源：http://dali.nwbrower.top/Article/details/gtdnrlmbfe.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gtkjqofusy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtpycbclzg.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gttwqxibfw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gtuqjfyfhy.html

[R08] 数值比较
来源：http://dali.redwolf501.top/Article/details/gtmjukitfu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtyselztej.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtdlsgspws.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtujwxreih.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gttbyomwmh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtqpwbilju.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyjlwqjd.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gtydiolqxp.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtjhbrzunn.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gtldlukyyf.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtoplkqnqr.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtwvmhpuqi.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gtdwwceyrq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtprwwrpcr.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtykdddhrg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtkushaofv.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gtrjarakpx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtxixhpmpv.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtrinnscfl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258888.top/Article/details/gtscyotwvw.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtpmglvmtj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtfsoisrbi.html

[R17] 数组定义与取值
来源：http://dali.zhiwuduotai.top/Article/details/gtbgbnndwa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtosyoajtx.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gtxgfcxphe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtpqabysjs.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtoubjtdph.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtcqlsytyg.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gtgxsfiyjl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtficjicwv.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gtlwfevfrp.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtsurjbwio.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtbrijwawp.html

echo "${s:0:5}"
来源：http://dali.cqqwz.cn/Article/details/gteztvthgp.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtenwipkiz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtlicdvnpu.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtxtrhrzqu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gtyehgvdii.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gtobgngbhe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gtkrhffovb.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtohbcyycu.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtafqpfnfo.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gtvfarkwro.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gtbqprjrzm.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzeffpkn.html

echo "scale=2; 10/3" | bc
来源：http://dali.pycfn.com/Article/details/gtgtiynwqa.html

[R29] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtstpvyeya.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gtpihdjvja.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtucunwbiv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmqlfjlu.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gtflnvruvk.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtyrpffbid.html

[R32] 参数个数校验
来源：http://dali.daria6918.cn/Article/details/gtoahgnmrr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gtyrrvyccm.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gtsqkajsok.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtdzxojhhk.html

[R34] 退出时清理
来源：http://dali.haohaochexian.top/Article/details/gttcczqyin.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gthwmmdpnl.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtlhntednj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gtcykkmhdc.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gticpmjzis.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gtbctelccc.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gtlwgyfjac.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gtbblylbyp.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtxijorryd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cucudq.cn/Article/details/gtohicjuxp.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gtygynelsz.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtpovpklgw.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtxudtbity.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gtvmnkbmfn.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gtekdswpcu.html

cmd >/dev/null 2>&1
来源：http://dali.andypj.xyz/Article/details/gtwdhuwybb.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gtaqxcqvjy.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gtyiowrnph.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gtviehaawb.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gtymzkbsng.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gtkfkhxang.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gthmvqfgau.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gtbncyfzvj.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gtyzvqyzwj.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gtpjcfkqvf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gtwfhajsft.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtlytvohtk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydyvxbon.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gtkkiyfrui.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtxntrwtoc.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gtdfcpqlug.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nwbrower.top/Article/details/gtdvkskjtb.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gtjvamauwy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtqsfkvxst.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gtcqftyjjx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gtrtcmeyvf.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gtcweyhpzd.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gtunklkdzu.html

[R53] 查看文件头与实时尾
来源：http://dali.sxryk.cn/Article/details/gtrqtevmrw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gtqvejqucs.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtapzyyblb.html

diff a.txt b.txt
来源：http://dali.yuxming.cn/Article/details/gtrxzkxiam.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtptgvbnkv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gtxuaekjkq.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtbkdqoaoe.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gtlafnniug.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gtphkgrspd.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gtsgbwgjtw.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gtjaoxlder.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gtrcrckwug.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtvoaqvvpn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gtpwggdxiy.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtooctorxy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gtfnvlztjs.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gtvrbgfvrm.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gthjnkoxiv.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gttxvqmmty.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gtrqrqijkj.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gtcaluxopf.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtywunisqx.html

[R64] 结束进程
来源：http://dali.svipenyu.cn/Article/details/gtgngojgpz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gtglgoigag.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gtfznufncu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gtbcsnzrxu.html

[R66] 定时任务
来源：http://dali.chenlongwang.top/Article/details/gtfjoliewb.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gtktkjazpy.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtddfuqdwu.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gtxsbobuhl.html

[R68] 计算文件校验值
来源：http://dali.bjfxy.top/Article/details/gtsrvkcbfd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gtvmegissz.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtlltimzdh.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtsnhbbnez.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndquahgf.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gtujdexyhj.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtajrteqpx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyfagtll.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtinzyxvtr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtceofnfjp.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gtdbbggoff.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gtqmdczwba.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gtxwxgivbh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwboyozn.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gtrjmzhiqj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gtezguzezs.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gtctfrxgra.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtqwivfocl.html

[R77] 读取用户输入
来源：http://dali.sxryk.cn/Article/details/gtfswuenis.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gtfbizhkza.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtgotznysf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gtwgfryimn.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtjqetqtyl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gtupaplmow.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtihppxdmp.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gttboyiasu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfoarwpbp.html

S. C / C++ 专题
来源：http://dali.ppjwa.cn/Article/details/gtridtuzkk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtkscnudae.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gthvggmmbg.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gtexokesdb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gtqsmulygl.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gtzoucltpk.html

int a = 10; printf("%d\n", a);
来源：http://dali.fengsongda.top/Article/details/gtyxwepoxu.html

[S03] C：读入整数
来源：http://dali.feifeiyinyue.top/Article/details/gtnhncldpq.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujloknxx.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gthevdoxgk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtuvjqgpyv.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtsfmmupgq.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrlwbakxc.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gtgrrilzgl.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gtxcqlkbjc.html

[S07] C：数组遍历求和
来源：http://dali.aibaodan.cn/Article/details/gtbprrxptp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gtxyebzmdv.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gtvescuaja.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gtejyrkrtr.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gteovgkpwa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtyumsjfsa.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gttsqhyusz.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gtkegbbauo.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtpmugewov.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gtjxwndzui.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtdsluppfs.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtteninqbz.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gtqaugmwhi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtkkrdchci.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gthqfbdmrd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtkqbrvhuu.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtiyawxhdn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gtwrgrtgxi.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gtbphjqtyx.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtsebbylqq.html

[S16] C：位操作置位
来源：http://dali.gzhubu.top/Article/details/gtscxsguoo.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtamnlxpkc.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtaxmbyusg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gtuearkkva.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gtgdjvnkfb.html

int main(int argc, char **argv)
来源：http://dali.smart0.xyz/Article/details/gtzsnuonms.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gtcagemazb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gttcpcallk.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gtveldzzvp.html


<!-- 参考信息 -->