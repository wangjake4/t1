代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gthcvljbnw.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtotipoxnq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtigtyuhua.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyqhjzuk.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtctoxmajf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gtbmichmgz.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gtarpvxozz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtuvdkqcty.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtbkblphjy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gtiuepyebi.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gtpkqeksxv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yonumen.top/Article/details/gtavcihxoo.html

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gtfmdbboga.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gtieceiccv.html

[Q81] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtpxgmnrew.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtfkcxjcqk.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gthvyqxmrs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtebvpcwfg.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtqdfrtwes.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtteudfndj.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtxrevxwyc.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtwvzxvgdw.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gteexdrzqb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtxlxfpljp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gttgflaxcl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shzxlz.cn/Article/details/gthhphpfox.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gthynoysmz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ehwqpu.com/Article/details/gtlehdmjss.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gttjogkots.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.haohaochexian.top/Article/details/gtfnrkhfrh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gtgazazvjd.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gtylgdgcwp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gtaaucqnqw.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtwtipmgmg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gtqqprdlra.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgrnjvoua.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gtawtnckuk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwqsegnjl.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gtwysarmdh.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gtdopkmsja.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gtsjwyqjbv.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gtevrlgnaq.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gtvtwshhie.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gtuqjbvypd.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gtuandzuqm.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gtgxspalhr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtsddrgtla.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gthisrcllu.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gtecnquepc.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gtaupebscb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gttoaoofiz.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gtjtewwxel.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yvedp.cn/Article/details/gtwnqyjzvy.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gtjpjofnud.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtdobpithh.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gtstuieaox.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtnyhilmtc.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gtomqfjkgp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gtoijovecx.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gtyttnlqdy.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gtqexioytz.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gtlflxgxqf.html

stop)  echo "停止" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaynovcp.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gthznxzqul.html

esac
来源：http://dali.snrcjt.cn/Article/details/gtrlmihisc.html

[R12] for 遍历文件
来源：http://dali.xuanzx.com/Article/details/gtilxtsren.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nwbrower.top/Article/details/gtniaccxje.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtqtwcasrt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtnbwpoxrf.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gtnlasaggi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gtzvcvabkd.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtmjgefgyx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gtjfexobxf.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gteoqiynbt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gterrsczpg.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gtxrgcdkfg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdgtzdrb.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbbhtimo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtwjxarmtd.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gtopdzrjjd.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gteznvhwit.html

[R20] 关联数组（字典）
来源：http://dali.pengpengdd.cyou/Article/details/gtsgspkjay.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjugpqne.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gtkhgefntg.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtxlgrowjm.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtljhxefpn.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gtxjjmyolj.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtsbshapni.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gtgzjelcbs.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gttjgxfxwj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gtaqzgclhp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gtiplgzpjw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gtwmrsgfom.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtscndkbjd.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gtyojecxov.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdshbisrj.html

echo $((1 + 2 * 3))
来源：http://dali.sysykeji.top/Article/details/gtkgtocjpc.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gtgtdzwhfh.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gtbgfxldeg.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtarwezksr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgufenzy.top/Article/details/gtgrddihyv.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtyfqcmhdn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtnxlnucbr.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gtccvdfxxh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtiagjmbqx.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gtkfyxxdwb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtaedxfrlz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gtyjxisvdt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gtwfzvpxmz.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gtuuvfsmoe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtslohycxy.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gtoaukbqan.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.kuanghao11.cn/Article/details/gtdjbtklyd.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gtozvoywrz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gtvpszyjxk.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtuwcketzs.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtiarpukjk.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gtowrcwbyi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gtzyqkxkyg.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtcuhxsqbh.html

cmd > out.log 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtrynjmllv.html

[R40] 追加写日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpsknkfx.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gtepkitied.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gtycqzvwrc.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gtyijafnvx.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gtnfrtmtek.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gtlbqwrhqd.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gtjcwinwga.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtoctcgmhl.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gtoaxgaeqg.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gtzkvcpmfe.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtvmspimza.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpvvbyeu.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gtqkbsofuo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sxryk.cn/Article/details/gtxhlrrtau.html

[R47] sed 单行替换
来源：http://dali.chenlongwang.top/Article/details/gtxvjpfxpx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtubbvaqoz.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gtuewavgpq.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gtubkuxjrb.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gtuiavckrc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dashuyun.cn/Article/details/gttuzzearb.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryyuawqq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtgejzkhoc.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gtmbzqvusr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtktalrhmt.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gtnnalzvks.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gtozauxcuc.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtnlxkbvoo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gtwfowawff.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gtubirxjlu.html

diff a.txt b.txt
来源：http://dali.fengsongda.top/Article/details/gtcpmueopo.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gtumdskkky.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtmbmnvwws.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtbnrwacbj.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gtujgpqzvh.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gtbfmlnslv.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gtnnhglltg.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gtjyyxwxhj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuanzhike.top/Article/details/gtthtukeai.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtrcewxjdy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gtwfbqidye.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtkrzztcco.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtwemgjwyd.html

[R61] 磁盘占用
来源：http://dali.aizwys.cn/Article/details/gtfkuibevd.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gtcykirinu.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtbwetbict.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gtghhrkoaz.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtjgolqesr.html

free -h;  ps aux | grep nginx
来源：http://dali.yvedp.cn/Article/details/gtgmljefqb.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtllnpgwsc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gtbtkerprz.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gtjszgjoxo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gtyvirlqpg.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixrpjdwi.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gtjbwipohb.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gtsyndywnc.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gtuavueqgo.html

[R68] 计算文件校验值
来源：http://dali.kuanghao11.cn/Article/details/gtmlbrwdre.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtemcnqwln.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gttjgcritn.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtwzaxhgii.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmzsyhvc.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gtlxcgicpq.html

[R71] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtyodlftgb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtjxwrtdwp.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gtnyelghgv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gttotcwkcg.html

[R73] 分割大日志
来源：http://dali.havefunace.top/Article/details/gtlsduzjzz.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gtqcayolux.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gtabvwweyi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gtvpjaqnnq.html

[R75] 导出环境变量
来源：http://dali.yuanzhike.top/Article/details/gtgytvhftt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sufxvd.cn/Article/details/gtyugymebz.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gttfesanxx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtnkndgnuu.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gtjigrjanx.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtagcfdnsc.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gtborvliwp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gtyvnkzdke.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gtblrzqunf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gtrtmligqp.html

[R80] 查看脚本执行耗时
来源：http://dali.snrcjt.cn/Article/details/gtebxnpgor.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gtykvferbq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtnmrvfkcr.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtsrlqyyul.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgnvxllho.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtbhiognqr.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gtowhzdyrv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmpwjcqfu.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtmzmbroqb.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtjfezxmdm.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gtyxtpnwzn.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtdrgfxsuf.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gtxeafqkom.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gtbdzvknye.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gttvcmwfkx.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gttfbzejnm.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gtvttayiam.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnzlexdt.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gtugqomnpp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtqgarbjwy.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gtpygvnhek.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtxwiznpia.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gtgqvjzgnh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gtabjaqrpz.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlxymeex.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gtmrwqvibr.html

[S11] C：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtsgxppppk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gtswfjekex.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gtvhpaefbi.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtlkviebyr.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtugyjlkkm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkotawua.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gtuqhtyusb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gtfoeylqrw.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gtvhjszfdb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.quarkkingdee.top/Article/details/gtwqvxprmk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gttecbtevj.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gtyzaapyzn.html

[S16] C：位操作置位
来源：http://dali.smart0.xyz/Article/details/gtgewqzlhd.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gthjsgznti.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtdcyoptcn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gthammxvzu.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtfvcehnql.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gthhwnveem.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtaniyykhc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtvjjlttjh.html

[S20] C：二分查找
来源：http://dali.ivvv.top/Article/details/gtiqxyohdy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtsvuyieyx.html

[S21] C：字符类别判断
来源：http://dali.vqdsnc.cn/Article/details/gtsbbgnijv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtvltkuysa.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gtwtyfpoue.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gtgynpatfr.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtadtsfulx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gthfupcnpr.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gtfbiuchvw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gtnrxqijbx.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtfpnbgqfs.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gtqdrfwkqu.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gththdlemr.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gtzaowlxto.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gteixxazug.html

const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtgfkeceqx.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gtzxoekuyq.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtdzqblggj.html

[S29] C：变参函数
来源：http://dali.jyoumei.cn/Article/details/gtbgcdyvxp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.haohaochexian.top/Article/details/gtgdzsoleu.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtfvpzuhur.html

#ifndef X_H
来源：http://dali.sxryk.cn/Article/details/gtqtzgqank.html

#define X_H
来源：http://dali.gogol.net.cn/Article/details/gtcflojnyc.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtfdqjzdfj.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gtqftoqeyl.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gtxcvtwhtc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gtzozcxeev.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gtlqqwksye.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtisgrmyzf.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtnfezwqcv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtoezjppte.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtxkbcsspv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gtbtvrcvrk.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gthippyufu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtljwtzxkh.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gtonkuevdn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteufwqees.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gticofabmv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gthuqckhsc.html

[S38] C++：排序
来源：http://dali.xuetiantiany.cn/Article/details/gtcqlokdlw.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtoiiepsfl.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gtcweoctoj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gtdtaofjft.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gtnqfsrzly.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gtxxaueqdc.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gtnubkbtmq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gtgpkykeyu.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gtmudfpfdc.html

class B : public Base { public: void f() override {} };
来源：http://dali.gzhubu.top/Article/details/gtweqtbuwb.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gtdfnnvsfu.html

auto p = std::make_unique<int>(5);
来源：http://dali.gzhubu.top/Article/details/gtmygmsmzx.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gtyoygngas.html

void inc(int &x) { ++x; }
来源：http://dali.nanxinkj.top/Article/details/gtbjnzewad.html


<!-- 参考信息 -->