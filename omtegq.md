代发 wailian999

[Q80] 字符串截取
来源：http://dali.gzhubu.top/Article/details/gtoitmceuo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gttjhqgfpf.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtdzxhodoc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtksvzlclk.html

[Q82] 字符长度与字节长度
来源：http://dali.ydzc1.top/Article/details/gtbozsmepc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtcffehpnf.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gthwzdxtht.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtybbllqbu.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gtqyssmuby.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtbbbvhrel.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gttidwrbec.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gtlnvogptx.html

[Q86] 读取 JSON 字段
来源：http://dali.cheryme.top/Article/details/gtjivwzcer.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gtfhqfbiqr.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gtgdonaojo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gotoacloud.top/Article/details/gtyoesllvn.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gtwepwgfjx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sufxvd.cn/Article/details/gtrrwzbbhd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sxryk.cn/Article/details/gtpnmtiyuz.html

[Q89] 判断表是否存在
来源：http://dali.fengsongda.top/Article/details/gtybgcxrua.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtocsuemxy.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtqipsjvri.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gtmoowvsxi.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtkljixxgm.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbmowfqr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjayywhbc.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gtinacsuhu.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gteaziqeyk.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gtojymiuee.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gtoqtxqhae.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gtbdrrqgbs.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtwrravfnv.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gtqnvjtfwd.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gteteluukd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfchzzokh.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gtnlthoavp.html

name="${1:-default}"
来源：http://dali.daxiang520.top/Article/details/gtsjwwwfpo.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gtdkrdqvrv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtfbhmkhya.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtyosbyana.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtfujafatd.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gtliallsit.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gtjbohsyqz.html

[R09] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gtusrklzhc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gttovlbtxm.html

[R10] 正则匹配
来源：http://dali.zhoulong.xyz/Article/details/gtkwuwtrmy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtldmdcnyj.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gtrrtjcnqw.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gtbfztqbzx.html

start) echo "启动" ;;
来源：http://dali.cucudq.cn/Article/details/gtubfwvact.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gtpmagdljo.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gtycpdkawp.html

esac
来源：http://dali.zhengqikj.top/Article/details/gtxagqnzto.html

[R12] for 遍历文件
来源：http://dali.xuanzx.com/Article/details/gtlnatnsmd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtezifxbmc.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gtxeflztkc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtrmefxggc.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gtykvtsamo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtthrpjeev.html

[R15] while 逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaetmjytj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gttiizjxyl.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gtzoeqpumt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtknfbyzkb.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gtpazeyqtl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdwjmzva.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtednunvsg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gtjnrnhbdt.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtbrxzpjsr.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gtkrgyxfzi.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gtwwtdjcju.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtpuwgsotv.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtofusqdbg.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtngwbhota.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtuzjjvlke.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqadxbti.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtjhcbcmed.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gtquyipcnt.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnrxvtoe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gtlstmcbeb.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gtmiusldwo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fzhhl.top/Article/details/gtugaumzfj.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaozlgiq.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gtcfyirjdc.html

[R27] 算术展开
来源：http://dali.chenzaomai.com/Article/details/gtyfmonucy.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtpifkpynp.html

[R28] 浮点运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpjyatum.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgkmpjzl.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtaqhwbcym.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gtiniygkbq.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtazuakghs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gthxjwovnd.html

[R31] 局部变量
来源：http://dali.jqgfzy.top/Article/details/gtfqtjukzb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtizdvdcxn.html

[R32] 参数个数校验
来源：http://dali.iojbl.cn/Article/details/gteouytajb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtdlkekjnd.html

[R33] 捕获错误并提示行号
来源：http://dali.cashguo.top/Article/details/gtxuamlkjy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gtbwytrwtu.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gtcrttwdkz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtmyaqfuuo.html

[R35] 后台执行并等待
来源：http://dali.daria6918.cn/Article/details/gtfcveercf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gtpxofenmp.html

[R36] 并发执行多个任务
来源：http://dali.cheryme.top/Article/details/gtyfjdkoya.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gtozomflge.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gtheejvrdb.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxdxnrhrs.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gtvuhaawzc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gtiltlsren.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gtzphojyzm.html

cmd > out.log 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtzaqexntl.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gtnrwnpetj.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gtbduamzxg.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbazrsasq.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtatydoovz.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtqfgbucbh.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtgdqupigl.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gtleodbjhh.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gtyzaqxhda.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gtqghyheyg.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gthdhptkwq.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwczhtej.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gtwzwmgaef.html

[R46] 递归替换文件内容
来源：http://dali.zhiwuduotai.top/Article/details/gtodoihimb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gttpndknvw.html

[R47] sed 单行替换
来源：http://dali.jinqigufen.top/Article/details/gtltapvsyi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gtrezdkztz.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gtcoqojsoc.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtcvakvzki.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gtdyteqeuc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtfhmnhvvo.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtplmsdfku.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggxwlfaq.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsfxzifv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gtujwsygqy.html

[R52] 统计行数
来源：http://dali.shangyingyoupin.top/Article/details/gtybsibjfi.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtfoadxgre.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gtrafacifv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gthzjwidhr.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtpjhjshog.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhntnxth.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gtutiztgyq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtpgocunts.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gtnygghnsu.html

scp file user@host:/path/
来源：http://dali.hfpthk.cn/Article/details/gtehbwgilx.html

[R57] 远程执行命令
来源：http://dali.andypj.xyz/Article/details/gtgbmlefoq.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gtvicjmvsn.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gtaeflneto.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gtnvgtqlgp.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtxwlzuuzx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigfzy.top/Article/details/gtzfuurlqt.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gthvdgdzgc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtlpjxtaic.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gtxjklehiq.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gtcvjwilqi.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gtvpczsfeh.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gtysiglyww.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gtxqpzkabr.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtqazfmcfj.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtiqlhmlyl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtncrwtobb.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gtqlzqdohe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuxming.cn/Article/details/gtfhciqqlb.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtequopagm.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gtjtumbvqf.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gtxgiurdsk.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gttbgdrngj.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gtwbubzlbv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gttswjbzkl.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gththrifjf.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gtadbggsuh.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gtwtsveeyl.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtfrtivfmn.html

[R71] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtlwbnjqzw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pengpengdd.cyou/Article/details/gteizyzvpz.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gtvgftwpps.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtcjealolu.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtnulabfor.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gtmyxblzwh.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gtxvvjoxtq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gogol.net.cn/Article/details/gtdwcabykp.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtbimvvvfi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gthiyycotr.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gtzhmxuejg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtkzhqyrbj.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbjyjpbl.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gtgiljnnnf.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtazarjbkg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gtzxazcksm.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtizoegyxw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtlmxepsup.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjslbmsjb.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtdkaexfgg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtfrwtllzs.html

S. C / C++ 专题
来源：http://dali.gogol.net.cn/Article/details/gtxeepxhbm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvqmjnyfk.html

[S01] C：Hello World
来源：http://dali.xylfe.cn/Article/details/gtiofprixa.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gttohkgflk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtoubtorcv.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtoiuniixg.html

int a = 10; printf("%d\n", a);
来源：http://dali.jiagoushi.top/Article/details/gtjkqnbxep.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gtgrzmgalk.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtutrvrqtq.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gttqfggxmn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gtnphxeogx.html

[S05] C：字符串长度
来源：http://dali.hysaishi.cn/Article/details/gttjowgupy.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtenqgeaee.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gttzhnrmkv.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gtjlieacbi.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gtzsjzhpze.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gtlibskwtz.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtkfudxhnz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkspykkm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtujbqhgdd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtqxpccjck.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gtkwokfdjk.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugyfbjek.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtimadfolp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gtsaojpmjm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gtothniium.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtrdzbqvna.html

[S12] C：写文件
来源：http://dali.yj202588.top/Article/details/gtgowytysw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtdfwtwwfi.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdiekydn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gtmglgmbxb.html

[S14] C：枚举
来源：http://dali.daxiang520.top/Article/details/gtiibtowop.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gtmnklsgys.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gtcaxuovzr.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtvygsseiv.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gthvcmlkdn.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gtfslphofi.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtvpqjeomz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtnngbwuxb.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtwhvhfcaj.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtwzmfzbay.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtirszluyc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtesbrwsxh.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gtmizzbpom.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gttjkwxfnh.html

[S21] C：字符类别判断
来源：http://dali.fzhhl.top/Article/details/gtdmbgjlno.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gtyavunxdc.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtxrsviibf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gtxmeidwna.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gttgaosvmu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jiagoushi.top/Article/details/gtvggfniui.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gtibbzxurh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gtykaopxcs.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gtpmtwnerc.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gthylieqqi.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxifzhls.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gtzntgrvcq.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gthsgjdshv.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtiqiwwbyy.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gtmgemxwbg.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtvjaqkamh.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gtaisbuhoi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gtpddpsurz.html

[S30] C：头文件保护
来源：http://dali.xziqi.cn/Article/details/gtupxvswna.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gtxxxxuooq.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gtapcqzkwn.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gtsgfrgpzg.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtywsolydh.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gtjbuhmlez.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gtnogodgko.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gtkrjvgeqn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gtrtfpdcgk.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gtvceogkix.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gtvmmseqzh.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gtwijnmqfz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gteveybdvf.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gtthlvluzv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtspjhxqbu.html

[S36] C++：unordered_map
来源：http://dali.cqqwz.cn/Article/details/gtofhgazla.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gthszpsmfo.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gtgpzgprci.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gtbtpywcnv.html

[S38] C++：排序
来源：http://dali.aibaodan.cn/Article/details/gttrfutugc.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gtuvstgaeq.html

[S39] C++：自定义比较器排序
来源：http://dali.havefunace.top/Article/details/gtvvkijvps.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dashuyun.cn/Article/details/gtedzzastj.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gtxxerhrzw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gtixugdanm.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtpcfgetqr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujrfvjku.html

[S42] C++：继承与虚函数
来源：http://dali.andypj.xyz/Article/details/gtbmhcnrvi.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtfyspkvxf.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gtbuolutbq.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gtcuqhgmup.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gtpdmdixfd.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtayeemoqf.html

[S45] C++：lambda
来源：http://dali.yanxiufei.cn/Article/details/gtcpqsplrx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtbaupwyiq.html

[S46] C++：函数模板
来源：http://dali.daxiang520.top/Article/details/gtpaxxgkex.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gtrmyosvws.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtzofjvvpd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gtqktpnutf.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtiqoudvbg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daxiang520.top/Article/details/gtkvmuyunq.html

while (std::getline(in, line)) { }
来源：http://dali.fengsongda.top/Article/details/gtwkveszpz.html

[S49] C++：写文件
来源：http://dali.havefunace.top/Article/details/gtrtfdmsei.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gtycmjohyt.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gtetfngyug.html


<!-- 参考信息 -->