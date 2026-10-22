代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2kizgaabu.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gt2sagcjhob.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhoulong.xyz/Article/details/gt2zqztkxoj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2aqnqavbv.html

[Q61] 移动平均
来源：http://dali.sysykeji.top/Article/details/gt2indeaqfu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2opajjlug.html

[Q62] 分组占比
来源：http://dali.hywenlv.cn/Article/details/gt2enzszoxm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2rnqejwre.html

[Q63] 开启事务
来源：http://dali.pycfn.com/Article/details/gt2fglpwkwo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gt2ftimjkvt.html

[Q64] 提交事务
来源：http://dali.iojbl.cn/Article/details/gt2ssywcknf.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gt2ramxayvu.html

[Q65] 回滚事务
来源：http://dali.fzhhl.top/Article/details/gt2kyafdbyd.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gt2leboqfzw.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gt2viqgyuvg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcfbuha.html

[Q67] 设置隔离级别
来源：http://dali.cdnleiting.top/Article/details/gt2rbnraobk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gt2jknegnej.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gt2hbwnhhxa.html

SAVEPOINT sp1;
来源：http://dali.shzxlz.cn/Article/details/gt2oxiwakqg.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gt2zkwemwta.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gt2unkeslyd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gt2upsmgpaw.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gt2aqexsclv.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gt2kuuzwlsq.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gt2zpaegigs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekqabdap.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gt2zyeiksnk.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gt2armoyerm.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gt2fttoxbrs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2lgtfkcxq.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gt2ooklhnxv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gusguuwv.html

[Q75] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gt2lrgcseol.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2ckplinvw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gt2szuoxjto.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gt2xsscmcmx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gt2nallfijc.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gt2imhgmvvu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gt2krwxtmed.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2zzimzmcm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpijwonw.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2ybtheulb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhixingplan.top/Article/details/gt2wriieumh.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqoibjyl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2atoyosih.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gt2gfxdvmzn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258.top/Article/details/gt2ziaumjvi.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gt2yxqtwfls.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2zdjygugl.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oabdivfe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2srwpebrr.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gt2qjgepimj.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2qvpkzjru.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gt2wgdguglj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gt2ysytyjhl.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgufenzy.top/Article/details/gt2uvyetxam.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdnlqtfc.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gt2cekznurh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gt2ydzjywql.html

[Q88] 行转列（条件聚合）
来源：http://dali.xylfe.cn/Article/details/gt2tfclihhv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yanxiufei.cn/Article/details/gt2geatndzm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gt2dyvrleul.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gt2knmpowpo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2djnrenat.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gt2deddbodm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gt2aayieymy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2olimtaco.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gt2yftvfpno.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2obktrwjx.html

[R01] shebang 与严格模式
来源：http://dali.nanxuanxn.top/Article/details/gt2hivwfzez.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gt2mnigoaqs.html

set -euo pipefail
来源：http://dali.316326.xyz/Article/details/gt2yzosfmkk.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gt2sxawbrgo.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gt2bkvmqumx.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gt2nhetyrae.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gt2obgjaqbf.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gt2yukpswxy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gt2frkiemuf.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gt2virkkjqq.html

name="${1:-default}"
来源：http://dali.hywenlv.cn/Article/details/gt2unoajfbd.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvezaksm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gt2dnpqwkyy.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gt2xgahbjum.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yvedp.cn/Article/details/gt2tvnlfrhg.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gt2uaakdnid.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2exahidrw.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2qprtzjrt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gt2bmrhktsb.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gt2dvkkbxxu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcktmsqx.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gt2tywqhtuh.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gt2lebyiose.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfgeygpt.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gt2xvttqyle.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2vwsburra.html

esac
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibwyqyos.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gt2zfxoktps.html

for f in *.txt; do echo "$f"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwhrhrxc.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gt2uuqbsjmv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdeyfvw.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gt2eniatbdw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2uaxorwwk.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2wdgvjsxs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gt2housinin.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gt2xgtlgzem.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gt2qfyooftn.html

[R17] 数组定义与取值
来源：http://dali.birdmap.top/Article/details/gt2zdfpegbe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gt2vasrbdqv.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gt2byylazkw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2mswjkjlb.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gt2opcczzec.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gt2gtnqkviy.html

[R20] 关联数组（字典）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2suenseri.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gt2tgxxgnlr.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gt2azppevby.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gt2makhlxyk.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gt2mwbkgdss.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvytxiew.html

[R23] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gt2ojuzczdr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cucudq.cn/Article/details/gt2jhpcpsuz.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2ivaoouay.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gt2bqaklykf.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gt2xffgxapj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjtinwdw.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gt2gysghmua.html

now=$(date +%F); echo "$now"
来源：http://dali.xinyue.icu/Article/details/gt2dbfkxtbp.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gt2fctzvqvs.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gt2aieicysj.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gt2usifebup.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gt2bypapvms.html

[R29] 定义函数
来源：http://dali.ydzc1.top/Article/details/gt2rdlpbuxu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2efpefayb.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gt2zvessttd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gt2djicmttc.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gt2hftprgxd.html

f() { local x=1; echo "$x"; }
来源：http://dali.sufxvd.cn/Article/details/gt2ddgiimzd.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gt2sngpovda.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gt2skonugam.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gt2mdltrvec.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gt2oscjrexo.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gt2xfmrflju.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gt2cowrmgmv.html

[R35] 后台执行并等待
来源：http://dali.hnqzz.top/Article/details/gt2eerhgpmj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gt2ekhjiele.html

[R36] 并发执行多个任务
来源：http://dali.ydzc1.top/Article/details/gt2bzgpncfz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gt2lnfsuolz.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gt2wmfbaflt.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gt2hskitavw.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gt2febqvare.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gt2mnxbjzlg.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gt2vzsobugg.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdbritbr.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gt2fpwyxxkw.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gt2zfnoccvl.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjfiiyen.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gt2eifdckjo.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gt2ihkuobcq.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrldsoqi.html

[R43] 按名字查找文件
来源：http://dali.tian-w.cn/Article/details/gt2fboeeixr.html

find . -name "*.log" -type f
来源：http://dali.nanxuanxn.top/Article/details/gt2bgdjauwj.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gt2fisjdmll.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2wncvkszq.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gt2yiilsurq.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gt2vzfedrzt.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gt2lxpsrpmq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcizbgll.html

[R47] sed 单行替换
来源：http://dali.andypj.xyz/Article/details/gt2ufrpccpk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2mrrfinqa.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gt2kwwjivou.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2ckhwgmcp.html

[R49] awk 带条件
来源：http://dali.jinqigufen.top/Article/details/gt2pkhrpxuk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.quarkkingdee.top/Article/details/gt2kunitfrt.html

[R50] awk 求和
来源：http://dali.cashguo.top/Article/details/gt2gcywhkzl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.316326.xyz/Article/details/gt2azfupuvx.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gt2jrxsyoxy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gt2dpuinppd.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atfewnuk.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2xntyaquj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wezkibto.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gt2ddwwtgft.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gt2aljaurtk.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gt2iodwlvof.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxfycmmf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.birdmap.top/Article/details/gt2uxtcnwqd.html

[R56] 远程拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwcttlto.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gt2gmwwnvij.html

[R57] 远程执行命令
来源：http://dali.xylfe.cn/Article/details/gt2zkwnduwn.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gt2slaiskhv.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gt2fsjnlcvk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daria6918.cn/Article/details/gt2qjoanzyx.html

[R59] 发 POST JSON
来源：http://dali.shuidangran.top/Article/details/gt2slxqbair.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gt2cqswymuj.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2shfupgxq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbxjfcfr.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkozsyye.html

df -h;  du -sh *
来源：http://dali.yj20258888.top/Article/details/gt2kjmlrbag.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gt2xsxamyzl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gt2vcnetrqz.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gt2lkcodwvd.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gt2kusuxdxr.html

[R64] 结束进程
来源：http://dali.jyoumei.cn/Article/details/gt2iixaoikb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gt2fyuzpcuw.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gt2teqtypwy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gt2dljtcaxk.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gt2gmrceemo.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gt2axgkfhwt.html

[R67] 生成随机十六进制串
来源：http://dali.shangyingyoupin.top/Article/details/gt2duucfbju.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gt2gphclynj.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gt2xyowhrbh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uctsukog.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gt2dmbarbfz.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gt2tjiammrl.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gt2pvvdrnfc.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gt2ttvovamo.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2nimnizrq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gt2vrsmsabn.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gt2cxsxfdxq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gt2aszkpomv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uohdzlwa.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gt2sqjzfzcm.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqjnoxoh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwriphqz.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gt2ojdpmcbs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gt2bhjkjwsw.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrbjvxjq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gt2qtluahqj.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gt2xtjocwle.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gt2mvycegpu.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gt2qqkdrajv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eglfgdlv.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gt2bwfclxii.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gt2nibhcogj.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gt2vdtphabd.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gt2moxgifyc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huutgayn.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gt2rbpddnly.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2mufnzjae.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2ymjdrgfl.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gt2nevrgvyb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xinyue.icu/Article/details/gt2yqdvggma.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gt2kywkxacc.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gt2xbbifflt.html

[S03] C：读入整数
来源：http://dali.jiagoushi.top/Article/details/gt2khaoqvvn.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gt2mgucmvhz.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rricdacq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2xgcewbmk.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gt2iuupldit.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gt2eqpaqvav.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gt2moyuzuuh.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gt2zzmbmwxx.html

[S07] C：数组遍历求和
来源：http://dali.yuanzhike.top/Article/details/gt2xetyhimh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gccgnszf.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akfehked.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nrpadypq.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gt2goxpsbzw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gt2ppwayijg.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ildtwtiv.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gt2zkvvzrrn.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2petyskoe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzyietcj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdoginxw.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gt2vczqotvu.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gt2isrwollx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pejnpegl.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gt2scuqnvgo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jianghu66.top/Article/details/gt2wzzrierv.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gt2fizvujwz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqxkwakz.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2kwbfwofd.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gt2gqdltqod.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gt2bnwtajqk.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gt2effuqnpt.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2buhmccab.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gt2wvonhjxv.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gt2ybjgrgte.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gt2dmntyqiw.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gt2amqdkwjr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2llpebtrp.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikqlaznc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmoybdes.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gt2sssvsept.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tggqplbk.html

[S22] C：字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gt2fgszimry.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hsymsgyh.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gt2nnjmieip.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gt2cgtdejfg.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gt2flirkmwt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfjxxchi.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gt2umsqzelz.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gt2sgjkhpzp.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gt2egncycpi.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gt2tyinrxuc.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gt2uoyxieea.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2tlvzkxvb.html

[S28] C：静态变量
来源：http://dali.cdnleiting.top/Article/details/gt2rkgyhrqz.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gt2kggqxrhl.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ujoiwras.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gt2aveymgbn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2funkilmh.html


<!-- 参考信息 -->