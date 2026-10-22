代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqbyxfr.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gt2aylobbnm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2wmipklax.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gt2qvamsblr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2zbllnzyp.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojqqmkcg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tianlin.xyz/Article/details/gt2ahoyuidh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2rznuipfb.html

[Q61] 移动平均
来源：http://dali.kuanghao11.cn/Article/details/gt2qwjpjavq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2rsmeyyyf.html

[Q62] 分组占比
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sslqidvp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2uqkjgxot.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gt2myvcwluz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gt2vnfvdttx.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gt2qskkhwhz.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gt2stvzabpm.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gt2pdfmmyhd.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gt2lxyhiytq.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gt2klkepdba.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gt2jeapfyha.html

[Q67] 设置隔离级别
来源：http://dali.bjfxy.top/Article/details/gt2qphmpgyc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gt2blqsalax.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmmtksax.html

SAVEPOINT sp1;
来源：http://dali.hammf.cn/Article/details/gt2mmpramps.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gt2jktwtcqi.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gt2puiaciqg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nwbrower.top/Article/details/gt2nunkrcry.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gt2vfltsnaw.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gt2vuefbwnu.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gt2cysvaosl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gt2lxpwpoev.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gt2ecpdkdcv.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2ehmcrbge.html

[Q73] 查看表状态
来源：http://dali.xziqi.cn/Article/details/gt2bllzyctb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gt2rgxlgkol.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gt2hsvxeuoa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jizzybau.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2kvprpcyj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2jymowyup.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gt2ipctenoa.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gt2drkdboiy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfpxuzju.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gt2pxhtlmyj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gt2bmbvfhuq.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oferxwuk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gt2gcoehuai.html

[Q79] 字符串拼接
来源：http://dali.yj202588.top/Article/details/gt2xohmebho.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gt2okcmzzfj.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gt2ixmcvaia.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2urwodicq.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gt2xkzskxvx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prizsnpf.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gt2achtpvab.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2qhtqcnhz.html

[Q83] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gt2lsalknnp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkqezqfr.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzardqgc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2nsxlolvn.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gt2gmdmjtcz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gt2njynojyw.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gt2bfcudyto.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gt2eumcgwzh.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gt2jscdualx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gt2fhmmdgsh.html

[Q88] 行转列（条件聚合）
来源：http://dali.yanxiufei.cn/Article/details/gt2dhqiyzml.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gt2zoeedjdi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2xtbimsps.html

[Q89] 判断表是否存在
来源：http://dali.jqgufenzy.top/Article/details/gt2kirqpiee.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gt2jwppipoj.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gt2paficrqo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gt2bpfndftr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ggdkadfw.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxeyzowt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2xwmiclbp.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gt2gdiugqnw.html

#!/usr/bin/env bash
来源：http://dali.yj202588.top/Article/details/gt2ufnkkduj.html

set -euo pipefail
来源：http://dali.jlsjyb.cn/Article/details/gt2ecxylpcw.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gt2etrsciay.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gt2jjhixqwu.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gt2vyuyifru.html

readonly PI=3.14
来源：http://dali.hnqzz.top/Article/details/gt2egdktgvp.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gt2cwvcpvzd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gt2aepuhssm.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gt2ptxwuuhc.html

name="${1:-default}"
来源：http://dali.zhengqikj.top/Article/details/gt2shgtqzzf.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2pyuwgbtn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2ukuftxgz.html

[R07] if 判断文件
来源：http://dali.hywenlv.cn/Article/details/gt2aekxslqd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aueescat.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfbgjrjp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2bxgjnsur.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2juekqkgc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2yfdfsxun.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gt2hfantwlc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gt2bvxrsxeu.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gt2dbxfajtf.html

case "$1" in
来源：http://dali.jinqigufen.top/Article/details/gt2hrziypad.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2cmivyqhu.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2jnnszlfv.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258.top/Article/details/gt2dxrgjvqj.html

esac
来源：http://dali.zhixingplan.top/Article/details/gt2rgcnjyeb.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gt2zubqosis.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gt2ltfwebbn.html

[R13] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gt2oynuyppw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjuvpqfi.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gt2vohmuzom.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gt2ysvzhmzj.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2tpkedgsm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258888.top/Article/details/gt2uhjkqogb.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gt2oqlnubso.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gt2vuxjutep.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gt2xncmbgbu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hywenlv.cn/Article/details/gt2vxlekffi.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2avtbooah.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gt2teicdvom.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2dluacydc.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gt2ihsoeifq.html

[R20] 关联数组（字典）
来源：http://dali.yj202588.top/Article/details/gt2yxauyuly.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gt2fvxblxfz.html

[R21] 字符串长度
来源：http://dali.smart0.xyz/Article/details/gt2lswpzamx.html

echo "${#s}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsvfhgxr.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gt2bxpkquwo.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gt2dotxqhow.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gt2jemumntk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258.top/Article/details/gt2klofxqes.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2ypuxswxw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gt2fnklxnfx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iculbesh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuanzx.com/Article/details/gt2ffqgsxst.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gt2upjpnnch.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gt2lrszsutp.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gt2rzjpdeuv.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gt2yctejtxz.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gt2ljoerbih.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhqdppsn.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhatqwbh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gt2zoznduvm.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2uzatqxup.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gt2fcighvbw.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2brtjbydv.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wizuxbsb.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gt2zcqdjpqt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gt2fqgkumvt.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gt2tmtrikxh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gt2gcizzcob.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gt2izyopbuf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2tcdpntpq.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gt2uyywpnnb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gt2rffbzsin.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrtieong.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cashguo.top/Article/details/gt2zasvjafc.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gt2xcpkldzt.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gt2trngwowl.html

[R38] 管道串联
来源：http://dali.nanxuanxn.top/Article/details/gt2rtffxvji.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebswpyno.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2qypbahmz.html

cmd > out.log 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kchzqzfn.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gt2ullcpncv.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gt2cxsairaf.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gt2uyxlclmt.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gt2sblhtncr.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gt2bdefpmvl.html

wc -l < a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2ujgobnju.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gt2mtzosgml.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gt2xjeqetlx.html

[R44] 按修改时间查找
来源：http://dali.xziqi.cn/Article/details/gt2tiwfqjyw.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gt2nkoiqayb.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gt2ngxrepur.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gt2gjsobdvv.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gt2hxjklyab.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gt2ugnkwrdr.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gt2xtwjlkzp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2odszoyle.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gt2cgtsnkqn.html

awk '{print $1, $3}' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2rpywozjm.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gt2jcxnymmq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gt2ghkdubxl.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gt2owuvvumb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2mlhssdpn.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gt2sxqxgdeh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmldpnwt.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gt2hbzmjxjh.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gt2njqcfkmx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gt2jxokijdt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sxryk.cn/Article/details/gt2vjnwoviu.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gt2xwhhrwpa.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecnbzhub.html

[R55] 压缩与解压
来源：http://dali.havefunace.top/Article/details/gt2cdbznzqx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gt2yubjfuxy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zreluwza.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gt2armtkswy.html

[R57] 远程执行命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjenkwrn.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gt2kqwqycxd.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gt2fpzulkyr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fzhhl.top/Article/details/gt2spuagtnd.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gt2gqfmstbp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigfzy.top/Article/details/gt2xubhuxle.html

[R60] 只看 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2plnnljbu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gt2dyhcshtv.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gt2vjxzmjuv.html

df -h;  du -sh *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jctmrdzk.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gt2fcikgvos.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gt2fegvekhb.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gt2pkhasteg.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gt2odevajbw.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gt2tqfytgtn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gt2huwyzmkb.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swesvrvv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gt2prwdigsy.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gt2rdcxsxvp.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqkjedwv.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gt2moqgcjmb.html

openssl rand -hex 16
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojafppbe.html

[R68] 计算文件校验值
来源：http://dali.daxiang520.top/Article/details/gt2slgglsxk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2rckhxebz.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gt2dlyhhbnm.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gt2aitpdedb.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gt2gmwctqfx.html

date +%s;  date -d @1700000000
来源：http://dali.yuanzhike.top/Article/details/gt2osjfrdqs.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2ipieadfq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gt2zpuzsnrt.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gt2xbafakgc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gt2bwdxpypr.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gt2xelqwdck.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gt2iriiziup.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gt2juvuqafg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gt2mvziugrl.html

[R75] 导出环境变量
来源：http://dali.jqgufenzy.top/Article/details/gt2fgfybzzp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gt2qnrwuhux.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gt2eshwcisb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gt2dlltbacd.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqukxtpv.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gt2fitbbztb.html

[R78] 交互式菜单
来源：http://dali.haohaochexian.top/Article/details/gt2ibpsejmv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gt2zuermnzd.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gt2pvnnbvcd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfrgandl.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gt2rblcalpu.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gt2klvrhues.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2pobsuwar.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gt2ggcwrzyj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2flcpblwt.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2dllsmagg.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmvolozq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gt2yivenfcn.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gt2ihcdscqe.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gt2xgetourw.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gt2lzqmuasx.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gt2mboexdvd.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gt2fkuuxgrp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gt2smitjfjj.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gt2rarbvddh.html

strlen(s)
来源：http://dali.dianchejie.cn/Article/details/gt2xqgsyemw.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gt2detbhqdh.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gt2xozrdemy.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gt2efhriuwu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gt2qgmduvza.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gt2vzjtsmwn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gt2dijzgfgu.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gt2atprcryu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jpiodryn.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gt2fuqmfbyh.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2bmwpnhli.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2djrfrevx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gt2lodacbfn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shzxlz.cn/Article/details/gt2wrqdxiha.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukegrigo.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gt2uswizhlq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2gvgvutuy.html

[S13] C：宏定义
来源：http://dali.xuanzx.com/Article/details/gt2hzatbsyq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sysykeji.top/Article/details/gt2dgdxlhyq.html

[S14] C：枚举
来源：http://dali.shuidangran.top/Article/details/gt2vaxdcusy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gt2tmwkivvv.html

[S15] C：类型转换
来源：http://dali.shuidangran.top/Article/details/gt2udpmmhgy.html

(double) a / b
来源：http://dali.hnqzz.top/Article/details/gt2ofimrwnb.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gt2vksrqsml.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gt2lisoqqzt.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2poxasgrf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gt2cbfbsqbf.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2dlcnjdnw.html

int main(int argc, char **argv)
来源：http://dali.birdmap.top/Article/details/gt2ifpcgubw.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gt2lcluljei.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gt2rffgzqir.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phrcznda.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2ysohhbfl.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlcjbmlt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gt2gfrffovj.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gt2pznbzcao.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gt2xyqtkzyc.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gt2ibmlulsb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ufzgmcte.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gt2vzlxglsw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gt2wklhxfbo.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gt2ddojtlgl.html

memcpy(dst, src, n);
来源：http://dali.bjfxy.top/Article/details/gt2fmunmxvo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fffsyuor.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gt2jurquifj.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gt2cfkpobxm.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2qauojogo.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gt2troeefik.html


<!-- 参考信息 -->