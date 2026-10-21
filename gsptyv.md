代发 wailian999

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gthvvlouol.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtxwciheyu.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtacnzobqn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtnkcffwst.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gtnliinbyi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtmfxechaf.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtbibebqlp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtnvjetjqd.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtmpwvhacg.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtiggbtlhg.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gtcpgusuol.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gtrxkamfiz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gtexxjbobr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258.top/Article/details/gtjahkdolw.html

[Q87] JSON 字段做条件
来源：http://dali.aibaodan.cn/Article/details/gtefojethj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuanzx.com/Article/details/gtniywearw.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenlongwang.top/Article/details/gtdxvhyskb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtsgxfqojk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtzzpyxojd.html

[Q89] 判断表是否存在
来源：http://dali.guannengcc.top/Article/details/gttkrdflcd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gtalijgduj.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtmdtfdyzj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuanzx.com/Article/details/gtlmakjtqp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmhcpysjd.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtnowpacvf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtafilvlqu.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtleimsjln.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gtdthkxqnx.html

set -euo pipefail
来源：http://dali.chenjidiqi.icu/Article/details/gtxohsopya.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gtioplcepy.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtzlhkmnhn.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gtsenvovqi.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gtlgmphwmk.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtlbesobol.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gtguwxocvi.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gtlgiuasvu.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gthijrfigz.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtrbawbzov.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtnkyrafwn.html

[R07] if 判断文件
来源：http://dali.cdnleiting.top/Article/details/gtzmubljqf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gtrnfrayjw.html

[R08] 数值比较
来源：http://dali.316326.xyz/Article/details/gtgeoyhcyu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtayotzgeq.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtmprolpyn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gteozpucei.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gtntshghxt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gtevdruwed.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gtfdezpcof.html

case "$1" in
来源：http://dali.tanke756.top/Article/details/gtlggnoqys.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtqrkqlnbe.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtiejsbnzj.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gthkrutjqt.html

esac
来源：http://dali.hnxiangtu.top/Article/details/gthjlmvwxp.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gtrlijzvll.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtqthyyhfu.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gthqfvdpmt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtnaqbhckr.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gtpttmwlen.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtpgsmwfrj.html

[R15] while 逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtrppwclqv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gtkanmzumc.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpszrwiww.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtglcrnhov.html

[R17] 数组定义与取值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybkeerhe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gtakcragip.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gtalhkqmoe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gtgghcrwvh.html

[R19] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdugdwili.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gthwfdzltw.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gteulaikpq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dianchejie.cn/Article/details/gttjttjfvv.html

[R21] 字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtqsezmvwe.html

echo "${#s}"
来源：http://dali.cdnleiting.top/Article/details/gthaqvehfs.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtmwpfjunu.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gtjcnzvvsd.html

[R23] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtxdogodxr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gtcprohnsc.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtmlwikuhb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gtbcvgrxas.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gtqqeczqgn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtwtsmjfza.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gttuchkzch.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gtbjjggngk.html

[R27] 算术展开
来源：http://dali.sxryk.cn/Article/details/gtmwkoxusa.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gtddnfthja.html

[R28] 浮点运算
来源：http://dali.yonumen.top/Article/details/gtchrxkvba.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gtstejttyy.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtkptzbqfv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gtjjfxmdti.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtcunzbmsj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttruatskd.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gtopqnagzr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gtbxwrdvuq.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowkkvcrh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtankfzfvm.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gtdapgqdxq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gtiouatbvl.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gtursexbgh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtdqdnmiod.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gtgdyjuemg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gtcqeuiknz.html

[R36] 并发执行多个任务
来源：http://dali.fengsongda.top/Article/details/gtynvhhsnz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuanzx.com/Article/details/gtmokvkkqo.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gtlsdtibtt.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtqqsbpcwt.html

[R38] 管道串联
来源：http://dali.chenjidiqi.icu/Article/details/gtmuozuvqq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yvedp.cn/Article/details/gtddyjgsrk.html

[R39] 重定向标准输出与错误
来源：http://dali.gotoacloud.top/Article/details/gtsbqluawj.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gtrrbsyqho.html

[R40] 追加写日志
来源：http://dali.ybcxt.top/Article/details/gtpfbyrccl.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtcrzrrrsx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtkhjymhqr.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtvmpwwheh.html

[R42] 输入重定向
来源：http://dali.snrcjt.cn/Article/details/gthwquuohv.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gtrpnthapc.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gtrrjiaptl.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gtyjoxzcpp.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gtahffrrdh.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gtwazqdjns.html

[R45] 批量删除
来源：http://dali.yj20258.top/Article/details/gtuvnhjysh.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gtorclnedw.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gtpsvvdovf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtlqcdewjd.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtkqritvjt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtbhmgrehj.html

[R48] awk 取指定列
来源：http://dali.jiagoushi.top/Article/details/gtqniqjlvt.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtpwwrwean.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gtanxpvgwl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gtyyzpfyen.html

[R50] awk 求和
来源：http://dali.andypj.xyz/Article/details/gtxjbmwlwi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtnpqgjooo.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gtjxghyiff.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shuidangran.top/Article/details/gtmemnqazr.html

[R52] 统计行数
来源：http://dali.nanxuanxn.top/Article/details/gtimraohzy.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlpkqrxv.html

[R53] 查看文件头与实时尾
来源：http://dali.hnqzz.top/Article/details/gttrwvbicu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.redwolf501.top/Article/details/gtbbblhalc.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gtuhzgioeg.html

diff a.txt b.txt
来源：http://dali.pycfn.com/Article/details/gtsybmpdvs.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gtaesqgdqr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtxuczjnjh.html

[R56] 远程拷贝
来源：http://dali.zhongyouzk.top/Article/details/gttwwauhig.html

scp file user@host:/path/
来源：http://dali.pengpengdd.cyou/Article/details/gtgrepmhms.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxdjfbjq.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gtcoiuyewj.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtryvydvez.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtntojtjgs.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtwyefqpgq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gtgufsazob.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtisdehtzy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gtvplnyxum.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gtvwhhssfp.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtcldthfai.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gtqmwmzlvk.html

du -ah . | sort -rh | head -10
来源：http://dali.aizwys.cn/Article/details/gtvvmxqdon.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtiwoqfnuy.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gtwkkbekcu.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfysmbol.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gtcqldando.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtwunsityf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaftxbwfi.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gtzxbhcxnb.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gtjawmteur.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtolimsgws.html

openssl rand -hex 16
来源：http://dali.chenjidiqi.icu/Article/details/gtyemiylww.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtpnbgaglf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gtxhhfgftb.html

[R69] 生成随机密码
来源：http://dali.hammf.cn/Article/details/gtfohkoixq.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtdcugymrp.html

[R70] 时间戳与互转
来源：http://dali.zhoulong.xyz/Article/details/gtjofaipec.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gtgkwplwis.html

[R71] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtktxvntmp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gtijeojfoi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gtmdustbbv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtiblhvvme.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtbnrilsbx.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gtviprzuku.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gtqxecukus.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gtnndagqum.html

[R75] 导出环境变量
来源：http://dali.dianchejie.cn/Article/details/gtjgakzrit.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gtibbuxmzk.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gttwhhohen.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtgrjvspjx.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtmbrgtwmx.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtckyuyxim.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gtgoznoosu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkymhphke.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gtacowimmz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gtrvubiblp.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gttezmspvx.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gtifdotazn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmpixlepa.html

S. C / C++ 专题
来源：http://dali.tianlin.xyz/Article/details/gtehofekxv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtllmgvafw.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gtghtmjcak.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gthlxeiklr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsbycjph.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtnwienjkd.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtmjmugpnp.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gtmjomvfgp.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gtgkjgpvng.html

[S04] C：字符串复制
来源：http://dali.c1oappe.top/Article/details/gtmtqrdgzy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gtvoxqzflj.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtviurcmaq.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gtpsnobsvv.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtuyucxiyl.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtfwddbtpg.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gtfmcydvbc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtafktmznl.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtpcrnhloq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gtksjykxvb.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gtyjauesej.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gtpixrtund.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gtbvwhmnzr.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gtpnvwfdcq.html

[S11] C：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtqppezlmi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gtmjqcpqyi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtnuhryfyf.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtmgxsjzpy.html

[S12] C：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvbnmigp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gthbkaorpm.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gtvgmzxciu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtsazoyczw.html

[S14] C：枚举
来源：http://dali.xziqi.cn/Article/details/gtjrltovoo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gtrjdpifom.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gteeeijqxq.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gtgspprtnk.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtyphffgur.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gtbmfzbnio.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtgjcvlyso.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gtgqktpcio.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gtittqgdkr.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gtuaqdpyuk.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gtigvulhmc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtfpziirua.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtvgqjsrak.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtoryoyuoe.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gtqxmxdwmc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gtlvkufzsi.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtglxwrgyk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gttlxluxvm.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwbpkchn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtvjsuxgxg.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtcznwhkju.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gttcvffstd.html

[S25] C：内存拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtxhycgdxq.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gtxabgkokc.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtsqszevgz.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gtzdytufqs.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gtplrslngv.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtnzytmfcs.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gtcqoohhxz.html

static int counter = 0;
来源：http://dali.hnqzz.top/Article/details/gtynzsjzvl.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gtloqahybl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sweek.top/Article/details/gtrrogxfsp.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gtqwjengat.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gtlusdfmqo.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gtyevvgxtq.html

#endif
来源：http://dali.yonumen.top/Article/details/gtjvydfqrt.html

[S31] C++：Hello World
来源：http://dali.havefunace.top/Article/details/gtmiiwnkew.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gtzxfsedgh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gtagnkhzhr.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtzofxfrsh.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtxhfkalek.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gtzrtvqlen.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtgzvlkrka.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gtjgluphlg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gtxhbpeyzn.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gtrjbyyhhn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfpredse.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtdbpyalst.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtkuggvefd.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gtnujnzfbb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gtqfithgra.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtwgfcsodi.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtdsgbwkdm.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gtdjbrrweg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daxiang520.top/Article/details/gtrjcqyiln.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gtzilshaow.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gtgpxwmmtc.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gthfwujtdt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtcaiuwgxw.html

[S42] C++：继承与虚函数
来源：http://dali.gzhubu.top/Article/details/gtiivtomwg.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gtjthxksrb.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtpuckzwha.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gtbnktaqnp.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gtofmbclcg.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpeqvdfvz.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gtfdprdtgd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hongshengwenyu.top/Article/details/gtswortwdw.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gtrajwphla.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj202588.top/Article/details/gtxawglxoo.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtvtplvjbr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcxdavmel.html

[S48] C++：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtyiibpudf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gtzasrfkcn.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gtqeiwrjvh.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtstvvktkd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtauiznuvg.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gtjerirnfx.html


<!-- 参考信息 -->