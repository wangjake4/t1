代发 wailian999

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gtgfhypxkj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gtrkpwzmhp.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtnnyabhfp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gtkawqkfuk.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gthsxgerkv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gtpvqeiwrs.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtwxgtswqk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gtkkbvrguz.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gtkhaihssd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtrjickjtn.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtxxdsiaia.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtidxyftmy.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gtjmuvivxn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtihnyjpis.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtltozmuml.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtokwvfqrz.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gtkhzbxdhc.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtkbvpzhbm.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gtmtdhygbe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtaooipuqn.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtjkgtunxm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gtlwxkiimh.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gtwhkbouwz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dianchejie.cn/Article/details/gtcwfffopn.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gtwdqeplwl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtnzarkatq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gtvmgzozgk.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gttsnsyqif.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gthlrrvevh.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gtvwxjsfdz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.snrcjt.cn/Article/details/gtjkhgtacg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttdmdznim.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtjwkocion.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdkrtitou.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gtzobdtszs.html

#!/usr/bin/env bash
来源：http://dali.ppjwa.cn/Article/details/gtqavgjjtp.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubxjoxvj.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gtfaifklxg.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtbgdjipzm.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gtmxxteyie.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gtswuwdvrf.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gtqwwkargh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenlongwang.top/Article/details/gtmpfcxpdi.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtriwluksq.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gtqjrmfbzw.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gtxoldpzjk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtvzzjqmlg.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gtdakzdadf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtqndaqkcf.html

[R08] 数值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxnrzdgm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtslkjezsm.html

[R09] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gtwbjyriie.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gtiwcxbqcx.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gtiipyjqmj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gtwvqgrile.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gtgehljyra.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gtquihofgj.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gtfadqmzae.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtktkuohli.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gtvqmubclw.html

esac
来源：http://dali.jqgfzy.top/Article/details/gtfkxnvacx.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gtimcxshkq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nwbrower.top/Article/details/gtawshrxlc.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtwgmeupsg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtyzcuscgi.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gteexlprlz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gtyabcvrod.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtjnqzubly.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtmqwfajwb.html

[R16] until 等待条件
来源：http://dali.zhixingplan.top/Article/details/gtdjnlvnol.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gteaurjlvi.html

[R17] 数组定义与取值
来源：http://dali.yj20258888.top/Article/details/gtbhwqqcig.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gtcazphdxy.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gtnrdyuhlg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzkraogi.html

[R19] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gtlirehnjv.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtoilbcque.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtvwuotxlp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtgahelexw.html

[R21] 字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtgzdmnmlu.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gtvysywqmw.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gtdqwmgrzj.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtqgqlkotp.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtgttvatmz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nwbrower.top/Article/details/gtmevajibx.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtwnkdrdot.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ydzc1.top/Article/details/gtdqtdkdun.html

[R25] 去后缀 / 去前缀
来源：http://dali.gogol.net.cn/Article/details/gtcldogynl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gtkwwhyknp.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gthxsiqvui.html

now=$(date +%F); echo "$now"
来源：http://dali.jiagoushi.top/Article/details/gtopprgnik.html

[R27] 算术展开
来源：http://dali.guannengcc.top/Article/details/gtbxeeuwtv.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gtrbozmjhq.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gtqwdjltpc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gtimfsdwas.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtsagclwpv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gtrocrxepx.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gtpzscoglt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gtwmhyxzfz.html

[R31] 局部变量
来源：http://dali.sysykeji.top/Article/details/gtlfqncxgo.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxuanxn.top/Article/details/gtmhtspirn.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gtqusddkwg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtiyhbtpax.html

[R33] 捕获错误并提示行号
来源：http://dali.cheryme.top/Article/details/gtcsvuwmoa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aizwys.cn/Article/details/gtnuuipwpc.html

[R34] 退出时清理
来源：http://dali.smart0.xyz/Article/details/gtrkqzrjej.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtmanpqpyo.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gthmzqkmqc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gtkbqajwnw.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gtbgrccwfb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gtvbsspmnc.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrhxdbgi.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gtyilgesfr.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gtlatynxqv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.iojbl.cn/Article/details/gttnvdtqln.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gtgxzoucdi.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gtfvkklwll.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtnojrelei.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhdidtnz.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gtxkltcupn.html

cmd >/dev/null 2>&1
来源：http://dali.jiagoushi.top/Article/details/gthpitmckz.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gtketyispq.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gtufigsqeq.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gtlzcwpbsu.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtsoqjlqhi.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gtinfzzaxy.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gtyknpasbo.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gtjwqxjzzl.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigfzy.top/Article/details/gtlumzdfkg.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gtrmsfiwoz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxuanxn.top/Article/details/gtbxrhulge.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtinkfbpvr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gtcpvktrvl.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtlrgiseau.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gtiacdlrpg.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gttbqtijoc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gtygohbljg.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gtqvsdzkrf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtbwodfcgv.html

[R51] 排序去重取前几
来源：http://dali.c1oappe.top/Article/details/gtcqdvwaeh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gtekwauolb.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gtkubexhqd.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtsqotajwi.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gthimianwh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.kuanghao11.cn/Article/details/gtlusksmae.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gtwosckrxr.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gtmiaixugv.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gtjlgdcgwo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gtvjipexgu.html

[R56] 远程拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtnklyifiu.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsprhxhd.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtjyoldcaq.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtcnlfdotz.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtjjuiepab.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gtsukdzlvh.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtnkymgqqm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuxming.cn/Article/details/gtgkhgcvzx.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtnrccmglx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gtjeppkxvz.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gtjqipgzjd.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gttqgpxyaa.html

[R62] 找最占空间的文件
来源：http://dali.yj20258.top/Article/details/gtzygfieva.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gtibywkanf.html

[R63] 内存与进程
来源：http://dali.jlsjyb.cn/Article/details/gtrrcffine.html

free -h;  ps aux | grep nginx
来源：http://dali.yuxming.cn/Article/details/gtabbsttsd.html

[R64] 结束进程
来源：http://dali.svipenyu.cn/Article/details/gtmaipmaba.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtunctnqpx.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtuzijkovl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtngnbgoou.html

[R66] 定时任务
来源：http://dali.gogol.net.cn/Article/details/gtipewzbmh.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtcupzilat.html

[R67] 生成随机十六进制串
来源：http://dali.tian-w.cn/Article/details/gtrqfpmctq.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvvlfbsi.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gttwrccpuj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gtavxafdgp.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gttyfxsxgh.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gtrnsgkfnc.html

[R70] 时间戳与互转
来源：http://dali.ppjwa.cn/Article/details/gttoskfzsu.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gtuyvwdbfp.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtictclezy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gtucelrusj.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtyuonzwsr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtrsbthalu.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gtudjxpzce.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtjgvujpqa.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gtxlpyuqpg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzqnvnjv.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtxdzqtlkf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shzxlz.cn/Article/details/gtjevczqze.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvjptjqe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtnukuqhba.html

[R77] 读取用户输入
来源：http://dali.tanke756.top/Article/details/gtlevnnpmb.html

read -rp "请输入: " ans
来源：http://dali.yongpay.top/Article/details/gtoozisipn.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gtrajddyqt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gtvniumsua.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gtrfuqoakt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gtwqbjharu.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gtirylijrp.html

time ./run.sh
来源：http://dali.cashguo.top/Article/details/gtttyzcqld.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxmcqfrff.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gtzuoplgok.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbyvrbghj.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtfpqjooqp.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtsifzutww.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gtqhmdluab.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gtqfmwnqev.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtwykdtpdl.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gteydjffsh.html

int x; scanf("%d", &x);
来源：http://dali.andypj.xyz/Article/details/gtxzgiicik.html

[S04] C：字符串复制
来源：http://dali.wangdashe.top/Article/details/gtvcktesun.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gtcwwwfwnr.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gthgovadcq.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gtrrkoeamq.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gteghoknza.html

strcmp(a, b) == 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmwyhzho.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gtirqbxmzf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtvmztxwau.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtsgpqlcyn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtinsgzfjr.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gtuvvhffej.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gtymzqkaxq.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gtieabxbpx.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtdpkjgqbb.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtjofkiyai.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtgoeaselt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtkjsekkqw.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtwjofurud.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtdfstorah.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtyksmncfv.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtrrejwcfu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtbdatkhsg.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gtxruevuxu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gtvessdlmi.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gtxddtszhi.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gtyaiantjr.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gtkhjcpvcr.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtczadvqsv.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtbybegzkw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shangyingyoupin.top/Article/details/gtomqxwhwd.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gtyklxpjrg.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtanxajipx.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gthapfgljo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtoazlezfq.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtptwhtdyt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtwjqijmzu.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtgymexfxb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gtzvxancgn.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtpkwgwujv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gttmnidgmv.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gtrsmwdtvp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gtayagcfpm.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gtnomyvals.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gtyjuljpep.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gtkpxcjgvc.html

memcpy(dst, src, n);
来源：http://dali.yonumen.top/Article/details/gtkesyemlb.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gtnefmdqxm.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gttrjvtvsd.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gtkfjwuixk.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtpgkqchta.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtfzawdexh.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gtscztdwye.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbdcvfbw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtktyheqsd.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtyylqojsr.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtqyddwzsc.html

#define X_H
来源：http://dali.cashguo.top/Article/details/gtolwhdvmr.html

#endif
来源：http://dali.smart0.xyz/Article/details/gtnauwskyu.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gtmdwxsefp.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gtjuhkmsow.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gttvwifacs.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gtlkyryupy.html

std::string s = "hi";  s += "!";
来源：http://dali.sweek.top/Article/details/gtdwrahflq.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gtckxmpmol.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtykifihwu.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gtqkatdlhw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gtnfluqwwy.html

[S35] C++：map
来源：http://dali.yonumen.top/Article/details/gttqwdicsx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtgnipxzfo.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gtnpggregj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gthngquzhi.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtldmcdmcl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtvevzylty.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gtqhqqionz.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gtklpxpmqb.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifvdsbep.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gtjymqqfca.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gtydazmley.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtfmsnnnvj.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtslxgnfqp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gtqlhfygxw.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtorobptvb.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gtppajbhcx.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gtfmardklo.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gtahivtbvt.html

[S44] C++：引用传参
来源：http://dali.9152youxi.cn/Article/details/gtcenntznp.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtgmenrtrb.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpkicwtj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gtivkeinkf.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gterompuan.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gtcscinxhz.html


<!-- 参考信息 -->