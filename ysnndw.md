代发 wailian999

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gtjvxtmgwi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gtsedqjmlg.html

[Q64] 提交事务
来源：http://dali.quarkkingdee.top/Article/details/gtbpykhszk.html

COMMIT;
来源：http://dali.shzxlz.cn/Article/details/gtudfshjzo.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gtrikgrzwm.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gtgxclyaok.html

[Q66] 行锁查询
来源：http://dali.redwolf501.top/Article/details/gttqhyuiph.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gtkghvidnc.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtpluykjax.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gtiicgbrdb.html

[Q68] 保存点
来源：http://dali.nanxuanxn.top/Article/details/gtebhehnpz.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtffhvoggn.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gtufdjacyx.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gttsmmpkcd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nwbrower.top/Article/details/gtgzqrpwju.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gtgfofdpvx.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gtuovytitu.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gtewhvubos.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gtqbkjhaow.html

[Q72] 查看索引
来源：http://dali.xziqi.cn/Article/details/gtnueqokwa.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzzipsnrp.html

[Q73] 查看表状态
来源：http://dali.sweek.top/Article/details/gtrurivhbh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtdbgjqoqa.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gtcegapwzw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gtuhodmcvf.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtjjnikhwn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyeidnen.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoayafdop.html

[Q76] 按天统计
来源：http://dali.daria6918.cn/Article/details/gtfmwabeng.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtwpggwslb.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gtrggdblzs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gtalvovvli.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gtpgafycjw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gotoacloud.top/Article/details/gtnivcgprm.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtccrunxar.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gtzssidwfp.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gtlxbwekmh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtlxnfhzlj.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gttoyybbls.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gtlanehcrv.html

[Q82] 字符长度与字节长度
来源：http://dali.ydzc1.top/Article/details/gtlvusjuic.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtpzbbpxza.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyatzjfug.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gteldrnaqi.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtkkylhrrl.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiwpuhui.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gtvmfebwjn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gtwlewnyon.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gteqxojxyb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtdzdwylcw.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gtmlbvlpqy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gtrnalutrs.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gtpigcnchc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtvpzbwqhd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtneottdrz.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gtsqlznsub.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gttxaakszk.html

[Q90] 生成序号列
来源：http://dali.ybcxt.top/Article/details/gtutcolqhh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtxkyjcsbp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtawbrdbxt.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtojqdhudh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtvnywtzlc.html

[R01] shebang 与严格模式
来源：http://dali.zhixingplan.top/Article/details/gtfyqsuapy.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtfhxrkqcx.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gtgtqyzvae.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gtfdfwcokk.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gttrkrynxo.html

[R03] 只读变量
来源：http://dali.tianlin.xyz/Article/details/gtafkeubto.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gtsacsbuir.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gtdzgjzdgw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.svipenyu.cn/Article/details/gteakikphr.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtvevcjslo.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcogaxqkc.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtirpljaix.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtchymmgix.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtzaunigtz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dianchejie.cn/Article/details/gtorlnqxwn.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtjctvyigs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gtcyzkcxtl.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gtcmynisei.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gtcubyackw.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtsmvpzlhv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gtwpshytvl.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtaervlbun.html

case "$1" in
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtailalrzq.html

start) echo "启动" ;;
来源：http://dali.yangfankeji.com/Article/details/gtlcpuwkei.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gtncvabkrz.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gtkgllozjm.html

esac
来源：http://dali.snrcjt.cn/Article/details/gtaaaqdjdq.html

[R12] for 遍历文件
来源：http://dali.nwbrower.top/Article/details/gtnntafadi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtagbhdcnb.html

[R13] for 计数循环
来源：http://dali.meibo888.top/Article/details/gtmnmwubdx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtmnseacar.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gtogigehvv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtaxlbyksh.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gttqwmngxv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gtoxjyyenp.html

[R16] until 等待条件
来源：http://dali.havefunace.top/Article/details/gtjxvhfims.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gttfhlcbef.html

[R17] 数组定义与取值
来源：http://dali.c1oappe.top/Article/details/gtdqcepxlp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtantsocdl.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gtsczaieag.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zycfv.cn/Article/details/gtbwphnjbr.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtizuntyiw.html

echo "${#arr[@]}"
来源：http://dali.cdnleiting.top/Article/details/gtkymlccml.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gtwephwrsp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gtmtzxebuf.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtmslyxpum.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gtcjlxkszi.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gttxxnrvgl.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gtlerofdij.html

[R23] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtqlvlrwtv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gtabsruvhz.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtjzczlomp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shuidangran.top/Article/details/gtsfbjmkwm.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gtzzfmbzhq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hammf.cn/Article/details/gtpunljmii.html

[R26] 命令替换
来源：http://dali.zhixingplan.top/Article/details/gtjqoqkohi.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gttgolbphf.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtqfmepcvk.html

echo $((1 + 2 * 3))
来源：http://dali.chenzaomai.com/Article/details/gtvdumnwkg.html

[R28] 浮点运算
来源：http://dali.cashguo.top/Article/details/gtxoifmkmn.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gtvxkquoav.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gtuouzdfpf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtuagdzzcx.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gtiddrvgpx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfifontx.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gtksptcxsr.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gtgeobvleg.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gtjytupxpp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlehkmgvf.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gtivfrggai.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gttwpvymkb.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtwqprldoq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtbmgfwdhs.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtbkuaqjzi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gtiuuumxgt.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gteezldbxc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gtsivotayy.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gtmcskqobg.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtaezbvvdo.html

[R38] 管道串联
来源：http://dali.meibo888.top/Article/details/gthqmkimci.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhiwuduotai.top/Article/details/gtlvcaelpl.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gtglbkidxw.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtinmttgkk.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtevzezpix.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtaxdxsdlq.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gtqrjvoqey.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gtwfotimxj.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gtovedjppj.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizsbqaph.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gtnifrmtux.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gtwsozowjv.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gtixgamlfp.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gtnnqtgueu.html

[R45] 批量删除
来源：http://dali.cheryme.top/Article/details/gtfzazqchd.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gtpekvnjbm.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtvjxdxpkx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gtamgntegg.html

[R47] sed 单行替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmfmtnmb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jyoumei.cn/Article/details/gteyyqmvlo.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gtgrwduhry.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtvduggulo.html

[R49] awk 带条件
来源：http://dali.cucudq.cn/Article/details/gtaotepfae.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhoulong.xyz/Article/details/gtwnqqikfz.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtuihpqqlm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtqqssspyv.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtgskoejoh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.smart0.xyz/Article/details/gtlytxnced.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gtwuylbbya.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskuowtbd.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpantckng.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gtnyiqpirb.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvblghte.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtedrbyztn.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gtqnigqpux.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gtcoqbdzpa.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gtwbwnnfeg.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gtetsfkckf.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtuffgcfvo.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gtczsiqeho.html

[R58] 下载文件
来源：http://dali.xuetiantiany.cn/Article/details/gtblnrfyiz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfvegphi.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtfzswrqek.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtohwgkwjy.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtpljcuyxv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gtptrnurwu.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtwdrlydel.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gtncjengfd.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtkvwqtdob.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtiikplwqi.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gtstkrkrmg.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gtxtlktnun.html

[R64] 结束进程
来源：http://dali.zhoulong.xyz/Article/details/gtpevyfaoc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxebqjvz.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gtcjrsvrto.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gtvdfiflnc.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gtlgorzasg.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gtwqrhrfqe.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gtvcyifrgr.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gthtrzustk.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtssfurwmr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gtuuadffpq.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gtyculjyiu.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gtsouaxpmb.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gthsbfaacq.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtjmcqajdc.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtoumfvplq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gtbdpbpqnh.html

[R72] 等待端口就绪
来源：http://dali.hfpthk.cn/Article/details/gthpbcbzcx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtqmryploj.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gtvcqwbhzn.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gtyiynlvzt.html

[R74] 批量重命名
来源：http://dali.mhx1999.top/Article/details/gtoeyhnhml.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtwqygrkst.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gtxgfmgkza.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gtwcegieno.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwngzygi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtfaemrmev.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtmsigmwxc.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gtmlngmgpd.html

[R78] 交互式菜单
来源：http://dali.ybcxt.top/Article/details/gtmsdshgmn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gtospipbnq.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gtulciufxo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gtiqxwhbdd.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gtkqtyoslp.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gtkyygavue.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtloxlqbfz.html

S. C / C++ 专题
来源：http://dali.aibaodan.cn/Article/details/gtalxhsceg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttnhdelhz.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gtouccqwkd.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gtbgyvhnxh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtsiaxrplu.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gtlbembeij.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gtdchhernf.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtvvnzmzdw.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxbbzbkz.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtrrqmepck.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuxming.cn/Article/details/gtjxtenykx.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gtlrtcvejv.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gtzeslbihj.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtkrwsiswi.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtmgxdvbqh.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gtycnvizyw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gtchaiiovv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gtqknqwkwz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgdjljnk.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gttmzixlch.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtyrzqsmih.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqywcbox.html

int *p = &a;  *p = 5;
来源：http://dali.chenlongwang.top/Article/details/gtqmsroltj.html

[S11] C：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtgjeqyzby.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gtftblogil.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gtpevtsztc.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbpvrtph.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtguvjrejc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtpykipdaj.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gtxwhoejve.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gtyydxlgwe.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gtbattwjta.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gturfrmchp.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gttjfrymru.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtjiufezah.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsmbdvfh.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gtouxhgbmd.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtwkhloflk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gtgzhokpan.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtkqvpufvg.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtzewpaulw.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gtwjfxadny.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtfqlhhbfr.html

[S20] C：二分查找
来源：http://dali.guowangkeji.top/Article/details/gtzbksqopw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtxsjoiejf.html

[S21] C：字符类别判断
来源：http://dali.hysaishi.cn/Article/details/gtaayyzqtx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gtsiqsysyw.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtxaxqfwwc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtejkujrbc.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtdvuzweal.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gteudioqbh.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gtqrtogskn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jiagoushi.top/Article/details/gtxhstaulh.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gtfwawrphj.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gtjyjjyrnb.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtfaqruues.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshqjolqb.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gtayzahrwq.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtppibnpnk.html

[S28] C：静态变量
来源：http://dali.sysykeji.top/Article/details/gtxkygrvhb.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gtcocrvuba.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtudfarskn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtbbqwtsgw.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gtuumrokhs.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gtitfthsnc.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtatfqrycz.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gtplgekwms.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gthlavymsn.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gtcvhitwgc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gtcjdzignr.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gtoiebczae.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtuvldswzb.html


<!-- 参考信息 -->