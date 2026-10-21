代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gtwrsinedm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gtcnaqqkjv.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gtendrkmgu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtjngaahzq.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgtqlxhp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gtjjbwqtxv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtencovgfv.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtoqerhqbm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gtivexfmfc.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgifliko.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gtjalwxlgy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtggvkomso.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gtdshwtizl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtamslivfh.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gtgfrsypil.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtuheskiie.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gtguorejor.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gtirpovrmi.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gtjfbwvivr.html

[R03] 只读变量
来源：http://dali.ehwqpu.com/Article/details/gtzyrzmuaa.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gthshgppyx.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gtptmjvosm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtvaqfbkme.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gtsivpgddr.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gtepkykwss.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtwznwrrgz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtlzrsuuzl.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gthtvxdkga.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gtroxpzlyc.html

[R08] 数值比较
来源：http://dali.zdqjudy.top/Article/details/gtyvcxvara.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cqqwz.cn/Article/details/gtjwknoaum.html

[R09] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gtgoekbrda.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gticmikmag.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gtlppinqnv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gttojgysiv.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtvqpxgryt.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gtxfijfynt.html

start) echo "启动" ;;
来源：http://dali.birdmap.top/Article/details/gthotqbdqk.html

stop)  echo "停止" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtdqxoohju.html

*)     echo "未知命令" ;;
来源：http://dali.ybcxt.top/Article/details/gtpnqloihd.html

esac
来源：http://dali.ivvv.top/Article/details/gtnrjckthf.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gtrxkfuyjp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.meibo888.top/Article/details/gtntgazdrx.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gtebqkisnr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtswsfujzi.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtoeixcycl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtyxobiwhl.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtinswmdmf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gtafniudma.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gtgddyrejc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gteadrunls.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gtcdgnhhsm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gttzwgxfwr.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gtreupifeo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gthsicbzkm.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtmtrsekmu.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gtjodsgwer.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtkquwaqrk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtzspupojs.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gttwogabjb.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtijikpvwr.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtmhzglfpt.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtvmaukrgb.html

[R23] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtoperlmwt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gtnbfhpblb.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtwedacaag.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gtbiscyirn.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpkqdsun.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gtwfpofrlk.html

[R26] 命令替换
来源：http://dali.wangshuangyany.cn/Article/details/gtpwlzieyg.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gtijozwzsv.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gtmlhchije.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gtodzikpnb.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtakufxuci.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtptjcezys.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gthwhbrcqx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gtdnuuwbno.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gtxdkjvfet.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gtmervrmkr.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gtwqjqhajy.html

f() { local x=1; echo "$x"; }
来源：http://dali.gogol.net.cn/Article/details/gtfmmlkrhi.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gtagzdkpoq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtjleihfgi.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gtplxiapfx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.iojbl.cn/Article/details/gtzsufokjr.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmylwcjl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtpbqlhxlk.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gtnrnhmabr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gtdpxchevn.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gtagbrnqtv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gtcxqffybm.html

[R37] 把输出赋给变量
来源：http://dali.meibo888.top/Article/details/gtlylcbzem.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gtvaknuyis.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gtxrxlecfg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gtauvmxbsc.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gtvjxlaeff.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtcfwbggta.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gtkeibkckw.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gtgcjvsebh.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtztfhbpto.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtnmazlelv.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqucgrtd.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtqpqzvwqp.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwevosxhf.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtykpvoykc.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gtqffmffer.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gtxqrmbjwq.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtezklrdjz.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gtsbeounma.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtsjvprzda.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gtcoqzvtej.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gtokjvjget.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtdyuuaiaw.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gtalyyejxt.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtjsfzdzin.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gtfroyhskt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gtmdpvwwma.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtoigfyeui.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gteuryrlua.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gtfbvmjxte.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.birdmap.top/Article/details/gtrvvccwtb.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gtwzocqwcc.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gtmyufsodb.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtimofgglr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gtmwphnobp.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtxzdczcnn.html

diff a.txt b.txt
来源：http://dali.fengsongda.top/Article/details/gtyfxxqiqd.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gtbqogizsh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sufxvd.cn/Article/details/gtbnrktxge.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwquxnjag.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gtdzxtrivp.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gtznzjxtff.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtdzzqpslf.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gtkcxmblbw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigfzy.top/Article/details/gtppfbepjw.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtamwcslge.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtcffhvmsw.html

[R60] 只看 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gtsildvywc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtasgtzavp.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gtlbewglqt.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gtixaocsct.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtqjzlrhux.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gtdjmevzxu.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gtymglslaf.html

free -h;  ps aux | grep nginx
来源：http://dali.yvedp.cn/Article/details/gtvypatump.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpfmzjue.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtlsnrdeae.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gtdanawfjq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gthppgdtuk.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gtlkmndtbx.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtkdueulbc.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gtlesovaer.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gtkcgmpaeb.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gtonqbgnqp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gtjsdhrsnd.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtztknjzmv.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gtuyaovusp.html

[R70] 时间戳与互转
来源：http://dali.snrcjt.cn/Article/details/gtghuzqfrb.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtsfwouryb.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorawckzd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gtpipyxues.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gtazzhkrfe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtiuiojlnt.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtczopudmf.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtkzevhcwn.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gtyfnbnjvp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gtghnuuykz.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtoiwtvgha.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gtkehbpdrz.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtykiubxbs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtwoyiophv.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtevlxxzdw.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gtbkioyfzp.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtnqieorlm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtzqcoskle.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gtwemqbecl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gtinnbuovb.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gtwheratwt.html

time ./run.sh
来源：http://dali.316326.xyz/Article/details/gtrztrohfq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvzfewcsm.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gtupzplgsh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrobesgwp.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gteozuemld.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gtjmcdfybg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gtxbpbpwgs.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtocalcupj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpfybveg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gtgazretbh.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gtdidyhhzt.html

[S04] C：字符串复制
来源：http://dali.zhengqikj.top/Article/details/gttqzhydfp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gtcrdzydqd.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtenumiapw.html

strlen(s)
来源：http://dali.xinyue.icu/Article/details/gtkuhocmmr.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtmqpnnlwk.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoeodhpn.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gtbsohvxgg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gthrmtnfeb.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gtuhnuloeb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtwaoqcmrf.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gtnmvkpybh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gttcfhnrts.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtuouuvlnz.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gtgblbmjhg.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtdtclaalj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sufxvd.cn/Article/details/gtwzpsngpg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gttzdaokdw.html

fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtgxccsqib.html

[S12] C：写文件
来源：http://dali.mhx1999.top/Article/details/gtpkjqqlbt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtlzhjgozl.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gtmkonzdzc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gtfygkeihi.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtwsveraph.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtowzjddrf.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtamlzooam.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gtvxhursqm.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gtxsocnqpf.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gtgzoblvem.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtvfzsoija.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gtvnhmfxhs.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtqqdodlzk.html

int main(int argc, char **argv)
来源：http://dali.xuetiantiany.cn/Article/details/gtwqdangxa.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gtlxfkjxrm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtbhyvbsry.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalihytar.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtdaqtfscl.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gtcacaqpni.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gtzgtzrfqp.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gtolygmgjx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gthuadruow.html

[S23] C：随机数
来源：http://dali.guowangkeji.top/Article/details/gtzhyasomg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gtxvrskqre.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gtnetrndpf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gtrrxbmydd.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtuxaqgrud.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gtprbwfnis.html

[S26] C：内存清零
来源：http://dali.cdnleiting.top/Article/details/gtghvybozo.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gtcniyxkis.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtrebcsnkw.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtmojkfixo.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtzecjrfxx.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gtmcheoqpc.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gtwagidrvq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gtgzlcugqz.html

[S30] C：头文件保护
来源：http://dali.sysykeji.top/Article/details/gtzhkezkuf.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtssxagscs.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gthuzseqbk.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gtraqoaebg.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtwraykcgu.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtelatlzya.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturpwxtjw.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gtyrgoqkbn.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gtzqdhvhiv.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gtopjlsyrs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gtgkpemyeg.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtvtiqivsb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtsgcsaxzy.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtqarxsdnp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtietokhnb.html

[S36] C++：unordered_map
来源：http://dali.daria6918.cn/Article/details/gtsbmtuvie.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtunhvjses.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gtbebmozfx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gtcahtwwlc.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtxxwyawya.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtvvscnspi.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gtubmjerrd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gtryoffbbx.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gtvakvpabf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gtgtthoehj.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gthgsejscd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhongyouzk.top/Article/details/gtajysdkki.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gtfyhwzrcd.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtduoloyfz.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gthmispvim.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gtnjgoxfqh.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gtapqmpsky.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gtqxcnouzp.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqedtqwd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gtqitfbofq.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gtbsnhvbpa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gtgqcwgkmw.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtdldhvufs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gtrnlwjuna.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtslseufuv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gtbrtbubmr.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneoaeqno.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gtcobtvivm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gtlienzyyu.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gthvffouyp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtzqdjljzt.html

[S51] C++：显式类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtizoyttdr.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupzuaolb.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gtnxpvujgg.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gtfifweaon.html

[S53] C++：移动语义
来源：http://dali.jqgufenzy.top/Article/details/gtnlnuezkz.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gtelpxilvk.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gtxhsyiuqn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gtbuldnjvx.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gtpjtekoxp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtwvodzutg.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtamxumhxl.html


<!-- 参考信息 -->